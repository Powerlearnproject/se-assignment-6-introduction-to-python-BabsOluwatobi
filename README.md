[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15338169&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python


 ***SOLUTION**

1. Python Basics:
Python is a high-level, interpreted programming language known for its simplicity and readability. Key features include:

- Easy to learn and read due to its clean syntax
- Dynamically typed, which allows for flexible coding
- Extensive standard library and third-party packages
- Support for multiple programming paradigms (OOP, functional, etc.)

Python is effective for:
- Web development (Django, Flask)
- Data analysis and visualization (Pandas, Matplotlib)
- Machine learning and AI (TensorFlow, PyTorch)
- Automation and scripting

2. Installing Python:
For Windows:
1. Download the installer from python.org
2. Run the installer, checking "Add Python to PATH"
3. Click "Install Now"

For macOS/Linux:
1. Use package manager (brew for macOS, apt for Ubuntu)
2. Run: `brew install python` or `sudo apt-get install python3`

Verify installation: Open terminal/command prompt and type `python --version`

Set up virtual environment:
```
python -m venv myenv
source myenv/bin/activate  # On Windows: myenv\Scripts\activate
```

3. Python Syntax and Semantics:
```python
print("Hello, World!")
```
This program uses the `print()` function to output text to the console. Python uses indentation for code blocks and doesn't require semicolons to end statements.

4. Data Types and Variables:
Basic data types: int, float, str, bool, list, tuple, dict, set

```python
age = 25  # int
height = 1.75  # float
name = "Alice"  # str
is_student = True  # bool

print(f"Name: {name}, Age: {age}, Height: {height}m, Student: {is_student}")
```

5. Control Structures:
```python
# if-else statement
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")

# for loop
for i in range(5):
    print(i)
```

6. Functions:
Functions in Python are reusable blocks of code that perform specific tasks.

```python
def add_numbers(a, b):
    return a + b

result = add_numbers(3, 5)
print(f"Sum: {result}")
```

7. Lists and Dictionaries:
```python
# List
numbers = [1, 2, 3, 4, 5]
numbers.append(6)
print(numbers[0])  # Access by index

# Dictionary
person = {"name": "John", "age": 30, "city": "New York"}
print(person["name"])  # Access by key
person["job"] = "Engineer"  # Add new key-value pair
```

8. Exception Handling:
```python
try:
    x = int(input("Enter a number: "))
    result = 10 / x
    print(f"Result: {result}")
except ValueError:
    print("Invalid input. Please enter a number.")
except ZeroDivisionError:
    print("Cannot divide by zero.")
finally:
    print("Operation completed.")
```

9. Modules and Packages:
Modules are Python files containing functions and variables. Packages are directories of modules.

```python
import math

radius = 5
area = math.pi * math.pow(radius, 2)
print(f"Area of circle: {area:.2f}")
```

10. File I/O:
Reading from a file:
```python
with open("input.txt", "r") as file:
    content = file.read()
    print(content)
```

Writing to a file:
```python
lines = ["Line 1", "Line 2", "Line 3"]
with open("output.txt", "w") as file:
    for line in lines:
        file.write(line + "\n")
        

***REFERENCES***
Python Software Foundation. (2024). Python Documentation. https://docs.python.org/3/
Van Rossum, G., & Drake, F. L. (2009). The Python Language Reference Manual. Network Theory Ltd.
Lutz, M. (2013). Learning Python: Powerful Object-Oriented Programming. O'Reilly Media, Inc.
CLAUDE.AI