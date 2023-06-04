# Learning-Python-ReadMe
# Best way to learn Python!

# Basic Operators

This section explains how to use basic operators in Python.

# Arithmetic Operators

- Just as any other programming languages, the addition, subtraction, multiplication, and division operators can be used with numbers

## number=1*8+6-2

## print("number")

- Try to predict what the answer will be. Does python follow order of operations?

- Another operator available is the modulo (%) operator, which returns the integer remainder of the division. dividend % divisor = remainder.

## test=11 % 3

## print("test")





# Classes and Objects

- Objects are an encapsulation of variables and functions into a single entity. Objects get their variables and functions from classes. Classes are essentially a template to create your objects.

- You can create multiple different objects that are of the same class(have the same variables and functions defined). However, each object contains independent copies of the variables defined in the class.

# init()

- The __init__() function, is a special function that is called when the class is being initiated. It's used for assigning values in a class.

# Dictionaries

- A dictionary is a data type similar to arrays, but works with keys and values instead of indexes. Each value stored in a dictionary can be accessed using a key, which is any type of object (a string, a number, a list, etc.) instead of using its index to address it.

- For example, a database of phone numbers could be stored using a dictionary

# Iterating over dictionaries

- Dictionaries can be iterated over, just like a list. However, a dictionary, unlike a list, does not keep the order of the values stored in it.





# Functions

# What are Functions?

- Functions are a convenient way to divide your code into useful blocks, allowing us to order our code, make it more readable, reuse it and save some time. Also functions are a key way to define interfaces so programmers can share their code.

- Where a block line is more Python code (even another block), and the block head is of the following format: block_keyword block_name(argument1,argument2, ...) Block keywords you already know are "if", "for", and "while".

- Functions in python are defined using the block keyword "def", followed with the function's name as the block's name

# How do you call functions in Python?

- Simply write the function's name followed by (), placing any required arguments within the brackets.

- Add a function named list_benefits() that returns the following list of strings: "More organized code", "More readable code", "Easier code reuse", "Allowing programmers to share and connect code together"

- Add a function named build_sentence(info) which receives a single argument containing a string and returns a sentence starting with the given string and ending with the string " is a benefit of functions!"


-For loops can iterate over a sequence of numbers using the "range" and "xrange" functions. The difference between range and xrange is that the range function returns a new list with numbers of that specified range, whereas xrange returns an iterator, which is more efficient. (Python 3 uses the range function, which acts like xrange). Note that the range function is zero based.

# Can we use "else" clause for loops?

- Unlike languages like C,CPP.. we can use else for loops. When the loop condition of "for" or "while" statement fails then code part in "else" is executed. If a break statement is executed inside the for loop then the "else" part is skipped. Note that the "else" part is executed even if there is a continue statement.





# Printing

- Python is a very simple language, and has a very straightforward syntax. It encourages programmers to program without boilerplate (prepared) code. The simplest directive in Python is the "print" directive - it simply prints out a line (and also includes a newline, unlike in C).

- There are two major Python versions, Python 2 and Python 3. Python 2 and 3 are quite different. This tutorial uses Python 3, because it more semantically correct and supports newer features.

- For example, one difference between Python 2 and 3 is the print statement. In Python 2, the "print" statement is not a function, and therefore it is invoked without parentheses. However, in Python 3, it is a function, and must be invoked with parentheses.

## To print a string in Python 3, just write:

## print("Hello,World!")

- You can do anything else, not only "Hello,World!".




# String Formatting

- Python uses C-style string formatting to create new, formatted strings. The "%" operator is used to format a set of variables enclosed in a "tuple" (a fixed size list), together with a format string, which contains normal text together with "argument specifiers", special symbols like "%s" and "%d".

- Let's say you have a variable called "name" with your user name in it, and you would then like to print(out a greeting to that user.)

## name="John" print("Hello, %s" % name)

## Here are some basic argument specifiers you should know:

## %s - String (or any object with a string representation, like numbers)

## %d - Integers

## %f - Floating point numbers

## %.<number of digits>f - Floating point numbers with a fixed amount of digits to the right of the dot.

%x/%X - Integers in hex representation (lowercase/uppercase)

 *String*

- Strings are bits of text. They can be defined as anything between quotes
  
  
  
  
  
  
  
  
  
  
*Basic String Operations*

- Strings are bits of text. They can be defined as anything between quotes:

astring= "Hello"

astring2= "Hello"
  
  
  
 
Loops

  
Can we use "else" clause for loops?

- Unlike languages like C,CPP.. we can use else for loops. When the loop condition of "for" or "while" statement fails then code part in "else" is executed. If a break statement is executed inside the for loop then the "else" part is skipped. Note that the "else" part is executed even if there is a continue statement.
  
  
- For loops can iterate over a sequence of numbers using the "range" and "xrange" functions. The difference between range and xrange is that the range function returns a new list with numbers of that specified range, whereas xrange returns an iterator, which is more efficient. (Python 3 uses the range function, which acts like xrange). Note that the range function is zero based.

  
  

Python Basics

What are the basics of python

Python is a popular high-level programming language known for its simplicity and readability. It is widely used in various fields such as web development, data analysis, artificial intelligence, and more. Here are some basics of Python:

Installation: Python can be downloaded and installed from the official Python website (python.org). It is available for different operating systems like Windows, macOS, and Linux.

Syntax: Python uses a clean and easy-to-understand syntax. It uses indentation (whitespace at the beginning of a line) to define code blocks instead of braces or keywords. This indentation is crucial for the structure and readability of the code.

Data Types: Python supports various data types, including:

Integers (int): Whole numbers, e.g., 42

Floating-Point Numbers (float): Numbers with decimal points, e.g., 3.14

Strings (str): Sequences of characters enclosed in single or double quotes, e.g., "Hello, World!"

Booleans (bool): Represents either True or False

Lists (list): Ordered collections of items enclosed in square brackets, e.g., [1, 2, 3]

Tuples (tuple): Similar to lists, but immutable (cannot be changed once created), e.g., (1, 2, 3)

Dictionaries (dict): Key-value pairs enclosed in curly braces, e.g., {"name": "John", "age": 25}

Variables: Variables are used to store data in memory for later use. In Python, you can assign a value to a variable using the assignment operator (=). The data type of a variable is inferred automatically based on the assigned value.

Control Flow: Python provides various control flow structures:

Conditional statements: if, elif, and else are used for decision-making based on certain conditions.

Loops: for and while loops are used for iterating over a sequence of items or executing a block of code repeatedly.

Functions: Functions allow you to encapsulate a block of code that performs a specific task. You can define your own functions using the def keyword. Functions can have parameters (inputs) and can return values.

Modules and Libraries: Python has a vast ecosystem of modules and libraries that extend its functionality. You can import these modules into your code using the import statement to leverage pre-built functions and classes. Examples include math for mathematical operations and random for random number generation.

Input and Output: Python allows you to interact with the user through the standard input (input()) and display output using the print() function.

These are just a few basics of Python to get you started. Python has extensive documentation and a supportive community, making it easy to find resources and examples for further learning.
