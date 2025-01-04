# Unexpected Null Return in JavaScript Function

This repository demonstrates a common yet easily overlooked bug in JavaScript functions: unexpected null returns when dealing with null or undefined parameters.  The `foo` function, as implemented, immediately returns null if either input parameter is null. This might not be desired behaviour in all situations.

## Problem
The provided `bug.js` file contains a JavaScript function that returns null if either of its input parameters are null. This abrupt termination could lead to unexpected behavior in larger applications.

## Solution
The `bugSolution.js` file provides an improved version of the function that handles null parameters more gracefully, providing an alternative behavior instead of simply returning null.  It checks for null values and substitutes them with a default value (0 in this case), ensuring the function always performs a calculation.

## How to run the code:
1. Clone the repository: `git clone <repository_url>`
2. Navigate to the directory: `cd Unexpected-Null-Return`
3. Run the code using a JavaScript runtime (e.g., Node.js): `node bug.js` and `node bugSolution.js`