# C++ Division by Zero Bug

This repository demonstrates a common runtime error in C++: division by zero. The `bug.cpp` file contains the erroneous code, while `bugSolution.cpp` provides a corrected version.

The bug occurs because the program attempts to divide `x` (10) by `y` (0), which is undefined behavior and typically leads to a program crash or unexpected results.

The solution involves adding a check to ensure that the divisor is not zero before performing the division. This check prevents the runtime error and makes the code more robust. 

This simple example highlights the importance of input validation and error handling in C++ to prevent such common errors. 