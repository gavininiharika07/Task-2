# Matrix Operations in C

## 📌 Project Description

This project is a **C program to perform basic matrix operations** using **functions and 2D arrays**.

The program supports:

* Matrix Addition
* Matrix Multiplication
* Matrix Transpose

A menu-driven approach using `switch-case` is used to select the required operation.

## 🎯 Objectives

* Understand and implement 2D arrays in C.
* Use functions for better modularity.
* Perform basic matrix operations.
* Understand matrix multiplication rules.
* Develop a menu-driven C program.

## ✨ Features

1. **Matrix Addition**

   * Adds two matrices of the same dimensions.

2. **Matrix Multiplication**

   * Multiplies two matrices when the number of columns of the first matrix equals the number of rows of the second matrix.

3. **Matrix Transpose**

   * Converts rows into columns and columns into rows.

## 🛠️ Technologies Used

* **Programming Language:** C
* **Concepts:** Functions, 2D Arrays, Loops, Switch-Case
* **Compiler:** GCC / Turbo C / VS Code

## 📂 Project Structure

```text
Matrix-Operations/
│
├── matrix_operations.c
└── README.md
```

## ▶️ How to Run

### Using VS Code

1. Create a file named `matrix_operations.c`.
2. Copy the C program into the file.
3. Open the terminal in VS Code.
4. Compile the program:

```bash
gcc matrix_operations.c -o matrix_operations
```

5. Run the program:

```bash
./matrix_operations
```

### On Windows

```bash
matrix_operations.exe
```

## 📋 Menu

```text
Matrix Operations
1. Matrix Addition
2. Matrix Multiplication
3. Matrix Transpose
Enter your choice:
```

## 💻 Sample Output

### Matrix Addition

```text
Enter your choice: 1

Enter rows and columns of matrices: 2 2

Enter Matrix A:
1 2
3 4

Enter Matrix B:
5 6
7 8

Result of Matrix Addition:
6   8
10  12
```

### Matrix Multiplication

```text
Enter your choice: 2

Enter rows and columns of Matrix A: 2 2

Enter Matrix A:
1 2
3 4

Enter rows and columns of Matrix B: 2 2

Enter Matrix B:
5 6
7 8

Result of Matrix Multiplication:
19  22
43  50
```

### Matrix Transpose

```text
Enter your choice: 3

Enter rows and columns of Matrix: 2 3

Enter Matrix:
1 2 3
4 5 6

Transpose of Matrix:
1   4
2   5
3   6
```

## 📚 Concepts Demonstrated

* 2D Arrays
* User-defined Functions
* Nested `for` Loops
* `switch-case`
* Matrix Addition
* Matrix Multiplication
* Matrix Transpose
* Modular Programming

## 🚀 Future Improvements

* Add matrix subtraction.
* Add scalar multiplication.
* Add matrix determinant calculation.
* Add matrix inverse calculation.
* Allow repeated operations without restarting the program.

## 👩‍💻 Author

*GAVINI NIHARIKA**

## 📄 License

This project is created for **educational and academic purposes**.
