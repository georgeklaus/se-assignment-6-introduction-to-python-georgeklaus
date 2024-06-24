[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15320145&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

A. **Python Basics : What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.**

 Python is a high-level, interpreted programming language known for its readability and simplicity. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming (Van Rossum, 2007)

 *Key features of python programing*

 -Readable and Maintainable Code : Python's syntax emphasizes readability, which reduces the cost of program maintenance.

 -Extensive Standard Library : Python's standard library supports many common programming tasks such as connecting to web servers, reading and modifying files, and working with data formats.

 -Interpreted Language : Python is an interpreted language, which means that Python code is executed line by line. This makes debugging easier and faster.

 -Dynamic Typing : Variables in Python do not need explicit declaration to reserve memory space. The declaration happens automatically when a value is assigned to a variable.

 -Portability : Python is available on many operating systems, making it a portable option.

 -Community Support : Python has a large and active community that contributes to a rich ecosystem of third-party packages and frameworks.

*Use Cases :* 
 
 1. Web Development: Frameworks like Django and Flask make it easy to build web applications.
 
 2. Data Science and Machine Learning: Libraries such as Pandas, NumPy, and TensorFlow are popular for data analysis and machine learning.
 
 3. Automation and Scripting: Python is widely used for writing small scripts to automate tasks.
 
 4. Software Development: Python is often used as a support language for software developers, for build control and management, testing, and in many other ways.


B. **Installing Python : Describe the steps to install Python on your operating system (Linux). Include how to verify the installation and set up a virtual environment.**

 1. Install Python using the following codes : (sudo apt update
sudo apt install python3)

 2. Verify the Installation using this code : (python3 --version)

 3. Install pip (Python package installer) using the following code : (sudo apt install python3-pip)

 4. Install *venv* for virtual environments using the following code : (sudo apt install python3-venv)

 5. Create a Virtual Environment using the following code : (python3 -m venv myenv)

 6. Activate the Virtual Environment using : (source myenv/bin/activate)

 7. Deactivate the Virtual Environment using  : (deactivate), (Van Rossum, 2007)



C. **Python Syntax and Semantics : Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.**

 A simple Python program that prints "Hello, World!" to the console:

 **# This is a comment**

print("Hello, World!")

*Explanation*

 -Comments: Start with # and are not executed by the interpreter.
 
 -print() function: A built-in function to output text to the console.

 -String literals: Enclosed in double quotes " or single quotes '. 


D. **Data Types and Variables : List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.**

 This is a list and description of varous datatypes used in python programing, (Hall & Stacey, 2009)

 -int: Integer numbers.

 -float: Floating-point numbers.

 -str: String of characters.

 -bool: Boolean values (True or False).

 -list: Ordered sequence of items.

 -tuple: Ordered, immutable sequence of items.

 -dict: Unordered collection of key-value pairs.

 *A short script that demonstrates how to create and use variables of different data types.*

 # Integer
a = 10
print(f"Integer: {a}")

# Float
b = 3.14
print(f"Float: {b}")

# String
c = "Hello"
print(f"String: {c}")

# Boolean
d = True
print(f"Boolean: {d}")

# List
e = [1, 2, 3]
print(f"List: {e}")

# Tuple
f = (4, 5, 6)
print(f"Tuple: {f}")

# Dictionary
g = {'key1': 'value1', 'key2': 'value2'}
print(f"Dictionary: {g}")


E. **Control Structures : Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.**

 -In Python, conditional statements and loops are fundamental constructs that control the flow of a program. They allow a program to make decisions and repeat actions based on certain conditions (Charatan & Kans, 2022)

1. Conditional Statements : Conditional statements allow a program to execute certain pieces of code based on whether a condition is true or false.

 x = 10

if x > 5:

    print("x is greater than 5")

else:

    print("x is less than or equal to 5")

2. For Loop : This iterates over a sequence (such as a list, tuple, string, or range) and executes a block of code for each item in the sequence.

 numbers = [1, 2, 3, 4, 5]

for number in numbers:

    print(number)


F. **Functions in Python : What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.**

 -Functions are reusable blocks of code that perform a specific task. They help in reducing code redundancy and improving code organization and readability (van Rossum & Drake, 2006)

 A Python function that takes two arguments and returns their sum and an example of how to call this function.

  def add(a, b):
  
    return a + b

*Calling the function*
  
   result = add(5, 3)
  
      print(result)  # Output: 8




G. **Lists and Dictionaries : Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.**

 A list is an ordered collection of elements that can be of different types. Lists are mutable, meaning their elements can be changed after the list is created while  a dictionary is an unordered collection of key-value pairs. Dictionaries are mutable, and the keys must be unique and immutable (like strings, numbers, or tuples), while the values can be of any type (Hall & Stacey, 2009)

  A script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both: 
   
   # List

numbers = [1, 2, 3, 4, 5]

print(numbers[2])  # Accessing third element

# Dictionary

person = {'name': 'Alice', 'age': 25}

print(person['name'])  # Accessing value by key

# Adding elements

numbers.append(6)

person['city'] = 'New York'

print(numbers)

print(person)


H. **Exception Handling : What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.**

 -Exception handling in Python is a mechanism for responding to runtime errors, allowing a program to continue execution or gracefully terminate. It is accomplished using *try*, *except*, *else*, and *finally* blocks (Juneau et al., 2010)

 try:

    # Code that may raise an exception

    result = 10 / 0

except ZeroDivisionError as e:

    print(f"Error: {e}")

finally:

    print("This will execute no matter what")



I. **Modules and Packages : Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.**

 -A module in Python is a file containing Python definitions and statements. The file name is the module name with the suffix .py added. Modules allow you to organize your code into manageable sections and reuse code across multiple programs (Vikram, 2024)

 A module can be created by saving a Python script with the .py extension. For example, create a file named mymodule.py
 
 Using a module: 

 **import** math

 **Using math module**

result = math.sqrt(16)

print(result)  # Output: 4.0


J. **File I/O : How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.**

 Reading from and writing to files in Python is a common task that can be accomplished using built-in functions.  To read from a file, you can use the open function with the mode 'r' (read). Use the read, readline, or readlines methods to read the content. To write to a file, you can use the open function with the mode 'w' (write) or 'a' (append). Use the write or writelines methods to write content to the file (van Rossum & Drake, 2006)

 1. **Reading from a File**

  **read_file.py**


def read_file(file_path):

    try:

        with open(file_path, 'r') as file:

            content = file.read()

            print(content)

    except FileNotFoundError:

        print(f"The file {file_path} does not exist.")

    except IOError:

        print("An error occurred while reading the file.")


  **Specify the path to your file**

file_path = 'example.txt'

read_file(file_path)


2. **Writing to a File**

 **write_file.py**

def write_to_file(file_path, lines):

    try:

        with open(file_path, 'w') as file:

            for line in lines:

                file.write(line + '\n')

    except IOError:

        print("An error occurred while writing to the file.")


**List of strings to write to the file**

lines_to_write = [

    "First line of text",

    "Second line of text",

    "Third line of text"

]

**Specify the path to your file**

file_path = 'output.txt'

write_to_file(file_path, lines_to_write)



**References**

Van Rossum, G. (2007, June). Python Programming Language. In USENIX annual technical conference (Vol. 41, No. 1, pp. 1-36).

Hall, T., & Stacey, J. P. (2009). Variables and Data Types. Python 3 for Absolute Beginners, 27-47.

Charatan, Q., & Kans, A. (2022). Python Control Structures: Selection. In Programming in Two Semesters: Using Python and Java (pp. 39-54). Cham: Springer International Publishing.

van Rossum, G., & Drake, F. L. (Eds.). (2006). An introduction to Python. Network Theory Limited.

Juneau, J., Baker, J., Ng, V., Soto, L., Wierzbicki, F., Juneau, J., ... & Wierzbicki, F. (2010). Exception Handling and Debugging. The Definitive Guide To Jython: Python For The Java™ Platform, 133-150.

https://www.shiksha.com/online-courses/articles/difference-between-module-and-package-in-python/#:~:text=In%20Python%2C%20both%20modules%20and,organized%20in%20a%20directory%20hierarchy.


**Submission Guidelines:**
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


