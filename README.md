# PYTHON FUNCTIONS
# INTRODUCTION
This repository contains Python function exercises that cover various fundamental aspects of function implementation, usage, and understanding in Python.
# THEORY
* Functions in Python are reusable blocks of code that perform a specific task. 
* They are defined using the def keyword, followed by the function name and parentheses containing any parameters.
* Functions improve code readability, reusability, and modularity.
# CONTENTS
### 1. Using the len() Function
* The len() function in Python returns the number of items in an object such as a list, string, tuple, or dictionary.
### 2. Greeting Function
* A Python function greet(name) that takes a person's name as input and prints a greeting message.
### 3. Finding the Maximum Value Without Built-in Functions
* A Python function find_maximum(numbers) that takes a list of integers and returns the maximum value by iterating through the list.
### 4. Local vs Global Variables
* Explain the difference between local and global variables in a Python function. Write a program where a global variable and a local variable have the same name and show how Python differentiates between them.
## * Global Variable:
* A global variable is declared outside any function, block, or class, making it accessible throughout the entire program. These variables can be read and modified by any function within the program unless explicitly restricted.
* It is available everywhere in the program.
* Exists as long as the program runs.
* Often used for data that multiple parts of a program need to share.
## * Local Variable:
* A local variable is declared inside a function or block, making it accessible only within that specific scope. Once the function exits, the variable is destroyed.
* It is Limited to the block or function where it's declared.
* Exists only during the execution of the function or block.
* Used for temporary data specific to a particular task.
### 5. Calculating Area with Default Arguments
* Create a function calculate_area(length, width=5) that calculates the area of a rectangle. If only the length is provided, the function should assume the width is 5. Show how the function behaves when called with and without the width argument.

# CONCLUSION
Python functions are one of the most essential tools in programming. They allow developers to encapsulate logic, make code reusable, and enhance modularity. By using functions, you can break complex problems into smaller, manageable pieces, making your code cleaner and easier to debug.
