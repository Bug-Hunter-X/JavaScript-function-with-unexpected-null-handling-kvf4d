# JavaScript Null Handling Bug

This repository demonstrates a common JavaScript bug related to null value handling in a function.

## Bug Description
The `foo` function in `bug.js` is intended to add two numbers. However, it does not correctly handle cases where one or both of the input arguments are `null` values.  This can lead to unexpected behavior or errors in larger applications.

## Solution
The corrected code in `bugSolution.js` addresses this bug by checking for null values and returning 0 instead of null in those cases. This makes the function more robust and reliable.

## How to run
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in your favorite text editor.
3. Run the JavaScript code using a Node.js environment (or a browser's console).
4. Observe the differences in output between the buggy and corrected versions.