# Unhandled NaN values in foo function

This repository demonstrates a common error in JavaScript:  the improper handling of `NaN` values. The original `foo` function fails to correctly manage `NaN` inputs, leading to unexpected behavior. The solution provides a more robust implementation.

## Bug
The `bug.js` file contains the faulty `foo` function.  Notice that when a `NaN` value is passed, the function simply returns `NaN` without any special handling.

## Solution
The `bugSolution.js` file shows a corrected `foo` function.  This version explicitly checks for `NaN` and returns an appropriate value or throws an error depending on the desired handling. This prevents unexpected results and improves the function's reliability.

## How to run
1. Clone this repository.
2. Open the `bug.js` and `bugSolution.js` files.
3. Run the JavaScript code in a Node.js environment or a web browser's console.