# Nullish Coalescing Assignment Operator Issue in JavaScript

This repository demonstrates an unexpected behavior in JavaScript when using nullish coalescing assignment (`??=`) operator with null or undefined values in function parameters.

## Bug Description
The issue arises when the function receives null or undefined values for its parameters. The intention might be to handle these cases gracefully, but the current code does not correctly reflect this intention. This could lead to unexpected behavior in the program.

## Bug Solution
The proposed solution handles null or undefined input parameters using explicit null checks or a more robust approach, preventing undefined behavior.

## How to Reproduce
1. Clone this repository
2. Run the `bug.js` file. Observe the unexpected behavior.
3. Run the `bugSolution.js` file. Observe the corrected behavior.
