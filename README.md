# Julia Function Bug

This repository demonstrates a subtle bug in a Julia function that involves conditional logic. The function is designed to square the input if it's positive, return 0 if it's zero, and return the negative of the square if it's negative.

The bug is related to potential unexpected behavior due to floating-point comparisons or data type issues. The solution provides a more robust approach that avoids these problems.

## How to reproduce

1. Clone this repository.
2. Run `bug.jl` using the Julia REPL.
3. Observe the output and compare it with the expected behavior.

## Solution

The `bugSolution.jl` file contains the corrected version of the function. This solution addresses the issue and ensures that the function behaves as intended in all cases.