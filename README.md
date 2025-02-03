# Hack Recursive Function Stack Overflow

This repository demonstrates a common error in Hack: stack overflow errors caused by unbounded recursion.  The `foo` function calculates factorials recursively.  For large inputs, this leads to a stack overflow. The solution provides an iterative approach to avoid this problem.

## Bug

The `bug.hack` file contains a Hack function that recursively calculates factorials.  For sufficiently large inputs, this function will cause a stack overflow error due to excessive recursive calls.

## Solution

The `bugSolution.hack` file shows how to rewrite the factorial calculation using iteration instead of recursion. This iterative approach avoids the stack overflow issue by not creating new stack frames for each recursive call.