0x00. Python - Hello, World.
Python is an easy to learn, powerful programming language. It has efficient high-level data structures and a simple but effective approach to object-oriented programming. Python’s elegant syntax and dynamic typing, together with its interpreted nature, make it an ideal language for scripting and rapid application development in many areas on most platforms.

Requirements
Python Scripts

    Allowed editors: vi, vim, emacs
    All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
    All your files should end with a new line
    The first line of all your files should be exactly #!/usr/bin/python3
    A README.md file at the root of the repo, containing a description of the repository
    A README.md file, at the root of the folder of this project, is mandatory
    Your code should use the pycodestyle (version 2.8.*)
    All your files must be executable
    The length of your files will be tested using wc
Shell Scripts

    Allowed editors: vi, vim, emacs
    All your scripts will be tested on Ubuntu 20.04 LTS
    All your scripts should be exactly two lines long (wc -l file should print 2)
    All your files should end with a new line
    The first line of all your files should be exactly #!/bin/bash
    All your files must be executable

C Scripts

    Allowed editors: vi, vim, emacs
    All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
    All your files should end with a new line
    Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
    You are not allowed to use global variables
    No more than 5 functions per file
    In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
    The prototypes of all your functions should be included in your header file called lists.h
    Don’t forget to push your header file
    All your header files should be include guarded

Pycodestyle is now the new standard of Python style code

Tasks.

0-run - Write a Shell script that runs a Python script.

1-run_inline - Write a Shell script that runs Python code.

2-print.py - Write a Python script that prints exactly "Programming is like building a multilingual puzzle, followed by a new line.

3-print_number.py - Complete this source code in order to print the integer stored in the variable number, followed by Battery street, followed by a new line.

4-print_float.py - Complete the source code in order to print the float stored in the variable number with a precision of 2 digits.

5-print_string.py - Complete this source code in order to print 3 times a string stored in the variable str, followed by its first 9 characters.

6-concat.py - Complete this source code to print Welcome to Holberton School!

7-edges.py - Complete this source code

8-concat_edges.py - Complete this source code to print object-oriented programming with Python, followed by a new line.

9-easter_egg.py - Write a Python script that prints “The Zen of Python”, by TimPeters, followed by a new line.

10-check_cycle.c - Write a function in C that checks if a singly linked list has a cycle in it.

    Prototype: int check_cycle(listint_t *list);
    Return: 0 if there is no cycle, 1 if there is a cycle

100-write.py - Write a Python script that prints exactly and that piece of art is useful - Dora Korpar, 2015-10-19, followed by a new line.

101-compile - Write a script that compiles a Python script file.

The Python file name will be stored in the environment variable $PYFILE

102-magic_calculation.py - Write the Python function def magic_calculation(a, b): that does exactly the same as the following Python bytecode:
3           0 LOAD_CONST               1 (98)
              3 LOAD_FAST                0 (a)
              6 LOAD_FAST                1 (b)
              9 BINARY_POWER
             10 BINARY_ADD
             11 RETURN_VALUE
lists.h - The prototypes of all your functions

README.md - file at the root of the repo, containing a description of the repository.
