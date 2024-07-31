Assignment: Introduction to Python
Instructions: Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

Questions:

1. Python Basics

What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a high-level, interpreted programming language known for its simplicity and readability. Its key features include:

Easy to Read and Write: Python's syntax is clear and straightforward, making it accessible for beginners.
Versatile: Python supports multiple programming paradigms, including procedural, object-oriented, and functional programming.
Extensive Libraries: Python has a rich standard library and a vibrant ecosystem of third-party packages.
Cross-Platform Compatibility: Python runs on various operating systems, such as Windows, macOS, and Linux.
Use Cases:

Web Development: Frameworks like Django and Flask make Python a popular choice for web applications.
Data Science: Libraries such as NumPy, pandas, and scikit-learn are used for data analysis and machine learning.
Automation: Python scripts are often used to automate repetitive tasks and system administration.
2. Installing Python:

Describe the steps to install Python on your operating system (Windows). Include how to verify the installation and set up a virtual environment.

Steps to Install Python on Windows:

Download Python: Go to the official Python website and download the installer for Windows.
Run the Installer: Execute the downloaded .exe file. Ensure you check the box "Add Python to PATH" before clicking "Install Now."
Verify Installation: Open Command Prompt and type python --version. If Python is installed correctly, it will display the version number.
Set Up a Virtual Environment:
Open Command Prompt.
Navigate to your project directory using cd path_to_your_directory.
Run python -m venv env to create a virtual environment named env.
Activate the environment by running env\Scripts\activate.
3. Python Syntax and Semantics:

Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

python
Copy code
print("Hello, World!")
Explanation:

print(): This is a built-in function in Python that outputs text to the console.
"Hello, World!": This is a string literal enclosed in double quotes, which is the text to be printed.
4. Data Types and Variables:

List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

Basic Data Types:

int: Integer values (e.g., 5, 42).
float: Floating-point numbers (e.g., 3.14, 2.718).
str: String (e.g., "hello", "world").
bool: Boolean values (True or False).
Example Script:

python
Copy code

# Creating variables of different data types

integer_var = 10
float_var = 20.5
string_var = "Hello, Python!"
boolean_var = True

# Printing the variables

print("Integer:", integer_var)
print("Float:", float_var)
print("String:", string_var)
print("Boolean:", boolean_var)
5. Control Structures:

Explain the use of conditional statements and loops in Python. Provide examples of an if-else statement and a for loop.

Conditional Statements: Allow the execution of code based on certain conditions.

Example of if-else:

python
Copy code
number = 10
if number > 0:
    print("Positive number")
else:
    print("Non-positive number")
Loops: Allow repeating a block of code multiple times.

Example of for loop:

python
Copy code
for i in range(5):
    print(i)
6. Functions in Python:

What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

Functions are reusable blocks of code that perform a specific task. They help in organizing code, avoiding repetition, and improving readability.

Example Function:

python
Copy code
def add_numbers(a, b):
    return a + b

# Calling the function

result = add_numbers(5, 3)
print("Sum:", result)
7. Lists and Dictionaries:

Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

Lists: Ordered collections that can contain elements of different types. Access elements by index.

Example List:

python
Copy code
numbers = [1, 2, 3, 4, 5]
print("List:", numbers)
print("First element:", numbers[0])
Dictionaries: Unordered collections of key-value pairs. Access values by key.

Example Dictionary:

python
Copy code
person = {"name": "Alice", "age": 30}
print("Dictionary:", person)
print("Name:", person["name"])
8. Exception Handling:

What is exception handling in Python? Provide an example of how to use try, except, and finally blocks to handle errors in a Python script.

Exception handling allows the program to continue running even if an error occurs. It involves using try, except, and finally blocks to manage exceptions.

Example:

python
Copy code
try:
    value = int(input("Enter a number: "))
    print("Value is:", value)
except ValueError:
    print("Invalid input. Please enter a valid number.")
finally:
    print("Execution complete.")
9. Modules and Packages:

Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the math module.

Modules: Files containing Python code that can be imported and used in other scripts.
Packages: Collections of modules grouped together in directories.
Example of Importing and Using a Module:

python
Copy code
import math

print("Square root of 16:", math.sqrt(16))
10. File I/O:

How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

Reading from a File:

python
Copy code
with open('example.txt', 'r') as file:
    content = file.read()
    print(content)
Writing to a File:

python
Copy code
lines = ["First line", "Second line", "Third line"]

with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + '\n')
