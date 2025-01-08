# JavaScript Null Handling in Arithmetic Operations

This repository demonstrates a common error in JavaScript: improper handling of `null` values in arithmetic operations.  The `bug.js` file shows the incorrect implementation, which throws an error if either input is `null`. The `bugSolution.js` file provides the corrected version, which handles `null` values gracefully.

## Bug

The original function `foo` does not properly handle `null` or `undefined` values. If either `a` or `b` is `null`, attempting to perform addition (`a + b`) will result in a runtime error.

## Solution

The solution explicitly checks if either `a` or `b` is `null` or `undefined`. If so, it returns 0, preventing the error. Otherwise, it performs the addition normally.

This example highlights the importance of input validation and robust error handling in JavaScript, especially when dealing with potentially null values.