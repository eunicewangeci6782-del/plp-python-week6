# Python Week 6 Assignment: Safe Functions

## Project Files

* `safe_tools.py` — Contains three Python functions that handle division by zero, invalid number conversion, and missing dictionary keys using exception handling.
* `README.md` — Describes the assignment files and explains how exception handling helps prevent program crashes.

## Why can't an if check catch "abc" on its own?

An `if` statement does not automatically know whether arbitrary text can be converted into an integer. When `int("abc")` is executed, Python raises a `ValueError`, so `try/except` catches the error and allows the program to continue without crashing.
