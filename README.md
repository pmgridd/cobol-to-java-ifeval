# COBOL to Java Migration: IFEVAL

This repository contains the Java migration of the COBOL `IFEVAL` program.

## Migration Overview

*   **Source**: [neopragma/cobol-samples/src/main/cobol/IFEVAL.CBL](https://github.com/neopragma/cobol-samples/blob/main/src/main/cobol/IFEVAL.CBL)
*   **Target**: Java
*   **Scope**: This project aims to migrate the COBOL `IFEVAL.CBL` program to a functionally equivalent Java application.
*   **Objectives**:
    *   Create a Java version of the `IFEVAL.CBL` program.
    *   Ensure the Java version is functionally equivalent to the original COBOL program.
    *   Provide clear and comprehensive documentation for the migrated code.

## Architecture

### Original COBOL Program

The original `IFEVAL.CBL` program is a simple COBOL program that demonstrates the use of `IF` statements. It takes a single numeric input and prints a message based on the value of the input.

### Target Java Application

The target Java application will be a simple command-line application that replicates the functionality of the original COBOL program.

## Getting Started

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/pmgridd/cobol-to-java-ifeval.git
    ```
2.  **Build the application**:
    ```bash
    javac src/main/java/com/example/ifeval/IfEval.java
    ```
3.  **Run the application**:
    ```bash
    java com.example.ifeval.IfEval <input-value>
    ```

## Usage Examples

```bash
java com.example.ifeval.IfEval 5
```

## Development Guide

### Contributing

Please follow the standard GitHub flow for contributions:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Commit your changes.
4.  Push your changes to your fork.
5.  Create a pull request.

### Development Workflow

*   **Branching**: Create a new branch for each new feature or bug fix.
*   **Commits**: Write clear and concise commit messages.
*   **Pull Requests**: Ensure your pull requests are well-documented and include a clear description of the changes.

### Coding Standards

*   Follow standard Java coding conventions.
*   Write clear and concise code.
*   Add comments to your code where necessary.

## Migration Status

| COBOL Program Section | Migration Status |
| --------------------- | ---------------- |
| `IDENTIFICATION DIVISION` | :white_check_mark: Complete |
| `DATA DIVISION` | :white_check_mark: Complete |
| `PROCEDURE DIVISION` | :white_check_mark: Complete |

## Troubleshooting

*   **Problem**: The application does not compile.
*   **Solution**: Ensure you have a recent version of the Java Development Kit (JDK) installed.

## License & Credits

*   **License**: This project is licensed under the MIT License.
*   **Credits**: This project is a migration of the `IFEVAL.CBL` program from the [neopragma/cobol-samples](https://github.com/neopragma/cobol-samples) repository.
