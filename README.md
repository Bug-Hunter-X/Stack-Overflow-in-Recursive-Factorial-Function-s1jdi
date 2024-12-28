This repository contains a Hack program that demonstrates a stack overflow error in a recursive function. The function calculates the factorial of a number.  If the input is too large, the recursion depth exceeds the system's limit resulting in a stack overflow.

The `bug.hack` file contains the buggy code, and `bugSolution.hack` provides a solution that avoids the stack overflow by using iteration instead of recursion. The solution is more efficient for larger input values.