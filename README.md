# Python ZeroDivisionError Bug

This repository demonstrates a common error in Python: the `ZeroDivisionError`.  The `calculate_average` function fails when provided an empty list, resulting in division by zero. The solution provides a more robust approach to handling this scenario.

## Bug Report

The original code lacks error handling for empty input lists, leading to a `ZeroDivisionError`. This is a runtime error that crashes the program.

## Solution

The solution checks for an empty list before performing the calculation.  If the list is empty, it returns 0, preventing the error.