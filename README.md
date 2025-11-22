Matrix Calculator

A simple Python-based Matrix Calculator that performs operations on one or two matrices using NumPy.

This program takes matrix inputs from the user and supports basic and advanced matrix operations.

Features

Inverse (if matrix is square & non-singular)

Determinant

Transpose

Addition and Subtraction (A ± B)

Matrix Multiplication (A × B)

Check whether two matrices are identical

Requirements

Install required packages:

pip install numpy pyfiglet


How to Run

python matrix_calculator.py

Follow the prompts to enter matrix sizes and elements, and then select operations.

Input Format

Enter elements of the matrix in a single line separated by space.

Example for a 2×2 matrix:

1 2 3 4

Notes

Matrix B is optional. Determinant and inverse are only computed for square matrices. Addition/subtraction must involve quantities of the same dimensionality. Multiplication requires (columns of A = rows of B).
