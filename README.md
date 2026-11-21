# Week 6 Assignment - Safe Functions

## Files

- `safe_tools.py` - Contains three safe functions that handle division, number conversion, and dictionary lookups.
- `unbreakable.py` - Contains the program for the second part of the Week 6 assignment.
- `README.md` - Describes the assignment and explains why an if check cannot catch the error from converting "abc" to an integer.

## Why can the if check not catch "abc" on its own?

An if check cannot catch the ValueError that happens when Python tries to convert "abc" to an integer. The error happens during the `int()` conversion, so we need `try` and `except` to catch the error and keep the program running.