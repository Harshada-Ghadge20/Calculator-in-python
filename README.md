# Python Calculator

A simple calculator application built using Python. This project performs basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

* Addition
* Subtraction
* Multiplication
* Division
* Simple and user-friendly input
* Error handling for invalid inputs
* Division by zero handling

## Technologies Used

* Python 3

## Project Structure

```text
calculator-project/
│
├── calculator.py
└── README.md
```

## Installation

1. Clone this repository:

```bash
git clone https://github.com/your-username/calculator-project.git
```

2. Go to the project folder:

```bash
cd calculator-project
```

3. Run the Python file:

```bash
python calculator.py
```

## Usage

After running the program, enter two numbers and choose an operation.

Example:

```text
Enter first number: 10
Enter second number: 5

Choose operation:
1. Addition
2. Subtraction
3. Multiplication
4. Division

Enter choice: 1

Result: 15
```

## Sample Code

```python
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error! Division by zero is not allowed."
    return a / b

print("Simple Calculator")
print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")

choice = input("Enter choice: ")

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

if choice == "1":
    print("Result:", add(num1, num2))
elif choice == "2":
    print("Result:", subtract(num1, num2))
elif choice == "3":
    print("Result:", multiply(num1, num2))
elif choice == "4":
    print("Result:", divide(num1, num2))
else:
    print("Invalid choice")
```

## Future Improvements

* Add more operations such as percentage, square root, and power
* Create a graphical user interface using Tkinter
* Add calculation history
* Improve input validation

## Author

Created by **Your Name**

## License

This project is open-source and free to use.
Also provide calculation of large numbers 
