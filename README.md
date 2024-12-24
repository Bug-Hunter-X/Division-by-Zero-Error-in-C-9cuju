# Division by Zero Bug in C

This repository demonstrates a common error in C programming: division by zero. The `bug.c` file contains code that attempts to divide an integer by zero, leading to undefined behavior. The `bugSolution.c` file provides a corrected version with robust error handling. 

## Problem

The `bug.c` file attempts to divide 10 by 0, which results in undefined behavior. Depending on the system and compiler, this may cause a program crash or unexpected results.

## Solution

The `bugSolution.c` file addresses this issue by checking if the divisor is zero before performing the division. If the divisor is zero, an error message is printed, and the program exits gracefully. This prevents undefined behavior and improves program robustness.