# Simple Calculator

A Java-based console application that performs basic arithmetic operations (addition, subtraction, multiplication, and division). This program is designed to be user-friendly and handles invalid inputs gracefully.

## Features
- **Basic Operations**: Supports addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`).
- **User-Friendly Interface**: Prompts the user for input and displays results in a clear format.
- **Input Validation**: Ensures that the user enters valid numbers and operations.
- **Loop for Multiple Calculations**: Allows the user to perform multiple calculations without restarting the program.

## How to Run the Program
1. **Compile the Java Code**:
   Open a terminal in the project directory and run:
   ```bash
   javac Main.java
Follow the Prompts:
Enter the first number.
Choose an operation (+, -, *, /).
Enter the second number.
View the result.
Choose to perform another calculation or exit.
Enter first number: 10
Enter operation (+, -, *, /): +
Enter second number: 5
Result: 15.00
Do you want to perform another calculation? (y/n): y
Enter first number: 20
Enter operation (+, -, *, /): /
Enter second number: 4
Result: 5.00
Do you want to perform another calculation? (y/n): 
Enter first number: abc
Invalid input. Please enter a numeric value.
Enter first number: 10
Enter operation (+, -, *, /): %
Invalid operation! Please use +, -, *, or /.
Enter operation (+, -, *, /): *
Enter second number: 3
Result: 30.00
