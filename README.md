# Unexpected 0 in Addition Function

This repository demonstrates a subtle bug in a JavaScript addition function. The function `foo` is designed to add two numbers, but unexpectedly returns 0 when either input is 0.

## Bug Description

The issue lies in the condition `a === 0 || b === 0`. While this correctly identifies cases where either `a` or `b` is strictly equal to 0, it causes the function to always return 0 even if both `a` and `b` have different values.

## Bug Solution

The solution involves modifying the conditional statement to only return 0 when both `a` and `b` are equal to 0. This ensures correct addition for other cases.

## How to run

1. Clone this repository.
2. Open `bug.js` to see the buggy code.
3. Open `bugSolution.js` to see the corrected code.
4. Run the JavaScript files in your preferred environment (e.g., Node.js, browser's console).