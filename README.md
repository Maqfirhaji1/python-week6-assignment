PLP Python Week 6 — Error Handling

This repository contains my Week 6 Python assignment for the PLP Python Programming course.

Files

safe_tools.py — Contains safe functions for division, number conversion, and dictionary lookups using try/except.

unbreakable.py — Demonstrates how try/except can safely handle invalid number conversion.

README.md — Provides an overview of the assignment and explains the use of exception handling.

What I Learned

This assignment demonstrates how Python's try/except statement can prevent a program from crashing when an expected error occurs.

Why can't the if check catch "abc" on its own?

An if statement can check a condition, but converting "abc" with int() causes Python to raise a ValueError during the conversion itself. The try/except structure catches that exception and allows the program to continue running safely.

Skills Practiced

Using try and except

Catching specific exceptions

Handling ZeroDivisionError

Handling ValueError

Handling KeyError

Writing reusable functions

Preventing programs from crashing

Testing functions with valid and invalid input

Expected Output

Running safe_tools.py should produce:

5.0
Cannot divide by zero
42
Not a number
82
Field not found


Running unbreakable.py should produce:

42
Invalid number

Repository

Repository name:

plp-python-week6


The repository should be public and contain:

plp-python-week6/
├── safe_tools.py
├── unbreakable.py
└── README.md