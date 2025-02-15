# Unexpected Results in MATLAB Function Due to Implicit Type Conversion

This repository demonstrates a subtle bug in a MATLAB function that arises from implicit type conversion between integer and floating-point data types. The function `myFunction.m` produces unexpected results under specific input conditions. The solution (`bugSolution.m`) addresses this by explicitly casting the input to the desired data type.

## Bug Description

The `myFunction.m` script contains a conditional statement that performs different calculations based on the input value. The implicit type conversion between integers and floating-point numbers leads to unexpected results when the input value is an integer that satisfies a certain condition.

## Bug Solution

The solution involves explicitly casting the input value to either an integer or floating-point data type, ensuring consistency and correctness of calculations irrespective of the input type.

## How to Reproduce

1. Clone the repository.
2. Open `bug.m` and `bugSolution.m` in MATLAB.
3. Run both scripts and compare the outputs.