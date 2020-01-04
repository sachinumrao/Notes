# Python Tutorial

Typing refers to type-checking in programming languages.

How to check (Strongly like python vs Weakly like js)and when to check:

Type-checking can be done at two stages -
Static - Data Types are checked before execution.
Dynamic - Data Types are checked during execution.

Python does type checking on the fly.
Python does Strong type-checking.

An Interpreted language executes its statements line by line.

## Memory Management
Memory management in Python is handled by the Python Memory Manager. 
The memory allocated by the manager is in form of a private heap space dedicated for Python. 
All Python objects are stored in this heap and being private, it is inaccessible to the programmer. 
Though, python does provide some core API functions to work upon the private heap space.
Additionally, Python has an in-built garbage collection to recycle the unused memory for the private heap space.

## Decorators
Decorators in Python are essentially functions that add functionality to an existing function in Python without changing the structure of the function itself. They are represented by the @decorator_name in Python and are called in bottom-up fashion

Pass by value: Copy of the actual object is passed. Changing the value of the copy of the object will not change the value of the original object.
Pass by reference: Reference to the actual object is passed. Changing the value of the new object will change the value of the original object.
In Python, arguments are passed by reference, i.e., reference to the actual object is passed.

