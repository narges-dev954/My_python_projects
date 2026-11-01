# My_python_projects
Add READMEdescription
# Simple Python Calculator

A basic command-line calculator built with Python that performs the four fundamental arithmetic operations: Addition, Subtraction, Multiplication, and Division.

## Features
- **Four Operations:** Supports `+`, `-`, `*`, and `/`.
- **Error Handling:** Includes a check for **Division by Zero** to prevent the program from crashing. If a user attempts to divide by zero, the program displays a friendly error message and requests a new input.

## How it Works
The calculator takes two numbers as input from the user and applies the chosen operator. It uses conditional logic (`if-elif-else`) to determine the operation and includes validation to ensure mathematical correctness.

## Error Handling Example
```python
if num2 == 0:
print("Error: Division by zero is not allowed. Please enter a non-zero number.")
