# RecursionError in Factorial Function

This repository demonstrates a common error in recursive functions: the lack of a base case for negative input. The factorial function is not defined for negative numbers, leading to infinite recursion and a `RecursionError`.

The `bug.py` file contains the erroneous code.  The `bugSolution.py` file provides a corrected version that handles negative input gracefully.

## How to reproduce the error

1. Clone this repository.
2. Run `bug.py` using a Python interpreter.
3. Observe the `RecursionError`. 

## Solution

The solution involves adding a check for negative input and raising a `ValueError` or returning an appropriate value (e.g., 1) for those cases.