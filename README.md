✅ Objective

Create a command-line calculator that performs basic arithmetic operations (addition, subtraction, multiplication, division) using Python.

🛠️ Tools Required
Python (any version 3.6+)

VS Code (or any text editor)

Terminal/Command Prompt

📄 Deliverable
A Python script file named calculator.py

🧠 Hints / Mini Guide
Define functions for each operation: add(), subtract(), multiply(), divide()

Use input() to take values and operation from user

Use a while loop to repeat the process until the user exits

Add error handling (like divide by zero or invalid input)

🧱 Code Structure (calculator.py)
python
Copy
Edit
# calculator.py

# Function Definitions
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error: Division by zero!"
    return a / b

# Main Loop
def calculator():
    print("Welcome to CLI Calculator!")
    print("Operations: + (add), - (subtract), * (multiply), / (divide), q (quit)")


# Run the calculator
if __name__ == "__main__":
    calculator()
✅ Expected Outcome
Well-structured and readable code

User can perform repeated calculations

Error messages for invalid input or division by zero

Clean CLI interface

🔁 Sample Run
text
Copy
Edit
Welcome to CLI Calculator!
Operations: + (add), - (subtract), * (multiply), / (divide), q (quit)

Enter operation (+, -, *, / or q to quit): +
Enter first number: 5
Enter second number: 3
Result: 8.0

Enter operation (+, -, *, / or q to quit): /
Enter first number: 10
Enter second number: 0
Result: Error: Division by zero!

Enter operation (+, -, *, / or q to quit): q
Exiting Calculator. Goodbye!
