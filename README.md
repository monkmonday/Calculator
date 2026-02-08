🧮 Simple Python Calculator

This is a basic command-line calculator written in Python.
It takes two numbers and an operator as input, then performs the selected arithmetic operation.

🚀 Features

Supports basic operations:

Addition (+)

Subtraction (-)

Multiplication (*)

Division (/)

Handles decimal numbers

Rounds the result to 3 decimal places

Displays an error message for invalid operators

🛠️ How It Works

The user enters an operator (+, -, *, /)

The user enters two numbers

The program performs the calculation

The result is printed on the screen

📄 Code Example
operator = input("enter an operator(+ ,- , * , /)")
num1 = float(input("Enter the 1st Number"))
num2 = float(input("Enter the 2nd Number"))

if operator == "+":
    result = num1 + num2
    print(round(result,3))
elif operator == "-":
    result = num1 - num2
    print(round(result,3))
elif operator == "*":
    result = num1 * num2
    print(round(result,3))
elif operator == "/":
    result = num1 / num2
    print(round(result,3))
else:
    print(f"{operator} is not valid one!")

▶️ How to Run

Make sure Python is installed

Save the file as calculator.py

Run the program:

python calculator.py

📌 Example Output
enter an operator(+ ,- , * , /) +
Enter the 1st Number 10
Enter the 2nd Number 3
13.0

📚 Beginner Friendly

This project is ideal for beginners learning:

Python input/output

Conditional statements

Basic arithmetic operations
