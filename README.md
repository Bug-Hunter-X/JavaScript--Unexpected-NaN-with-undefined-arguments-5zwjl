# JavaScript: Handling Undefined and Null Arguments

This repository demonstrates a common JavaScript issue: unexpected NaN results when dealing with undefined function arguments, even when null values are explicitly handled.  The `bug.js` file shows the flawed code, and `bugSolution.js` presents a corrected, more robust approach.

## Problem
The initial function correctly handles null values but fails to manage cases where arguments are undefined, resulting in NaN (Not a Number). This can be problematic and lead to unexpected behavior in applications.