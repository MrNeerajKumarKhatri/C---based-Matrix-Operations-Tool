# C-Based Matrix Operations Tool

A console-based matrix calculator written in C that performs common matrix operations while demonstrating pointers, dynamic memory allocation, recursion, and modular programming.

## Features

* Matrix addition
* Matrix subtraction
* Matrix multiplication
* Matrix transpose
* Matrix determinant
* Matrix trace
* Dynamic memory allocation
* Input validation
* Support for matrices up to `10 × 10`
* Interactive menu-driven interface
* Recursive determinant calculation

## Technologies Used

* C
* Standard C Library
* Pointers
* Dynamic Memory Allocation
* Recursion

## Matrix Operations

### Addition

Adds two matrices when both matrices have the same dimensions.

### Subtraction

Subtracts the second matrix from the first when both matrices have the same dimensions.

### Multiplication

Multiplies two matrices when the number of columns in the first matrix equals the number of rows in the second matrix.

### Transpose

Calculates the transpose of both matrices.

### Determinant

Calculates the determinant of square matrices using recursive cofactor expansion.

### Trace

Calculates the sum of the main diagonal elements of a square matrix.

## Example

```text
=======================================
    MATRIX CALCULATOR PROGRAM
=======================================

--- MATRIX 1 INPUT ---
Enter rows and columns (space separated): 2 2

Enter the matrix elements:
Row 1: 1 2
Row 2: 3 4

--- MATRIX 2 INPUT ---
Enter rows and columns (space separated): 2 2

Enter the matrix elements:
Row 1: 5 6
Row 2: 7 8
```

After entering the matrices, the program provides an interactive menu:

```text
=======================================
        MATRIX CALCULATOR MENU
=======================================
  1. Addition
  2. Subtraction
  3. Multiplication
  4. Transpose
  5. Determinant
  6. Exit
=======================================
```

## Concepts Demonstrated

This project was developed to strengthen fundamental C programming concepts, including:

* Functions
* Pointers
* Pointer-to-pointer usage
* Two-dimensional matrices
* Dynamic memory allocation
* `malloc()` and `free()`
* Loops
* Conditional statements
* Recursion
* Matrix algorithms
* Input validation
* Memory management

## Compilation

### Windows

Compile using GCC or MinGW:

```bash
gcc matrix_calculator.c -o matrix_calculator
```

Run:

```bash
matrix_calculator
```

### Linux

The current version contains Windows-specific functionality such as:

```c
#include <windows.h>
Sleep(2000);
system("cls");
```

Therefore, it requires modification for native Linux compilation.

## Limitations

* Maximum matrix size is `10 × 10`.
* Matrix elements are currently integers.
* The current version is Windows-specific because of screen-clearing and delay functions.
* Recursive determinant calculation becomes inefficient for larger matrices.
* Memory allocation error handling can be improved.

## Future Improvements

* [ ] Matrix inverse
* [ ] Rank calculation
* [x] Trace calculation
* [ ] Scalar multiplication
* [ ] Identity matrix generation
* [ ] Gaussian elimination
* [ ] Floating-point matrix support
* [ ] Cross-platform support
* [ ] Improved input validation
* [ ] Memory allocation error handling
* [ ] Separate header and source files
* [ ] Unit testing
* [ ] More advanced linear algebra operations

## Project Structure

```text
C---based-Matrix-Operations-Tool/
├── matrix_calculator.c
├── README.md
└── .gitignore
```

## Purpose

This project was created as a practical exercise in C programming and linear algebra. The main goal was to apply programming fundamentals such as pointers, dynamic memory allocation, recursion, functions, and memory management to a mathematical problem.

## License

This project is open source and available under the MIT License.

