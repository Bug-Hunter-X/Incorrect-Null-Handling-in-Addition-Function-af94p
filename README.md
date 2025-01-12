# Incorrect Null Handling in Addition Function

This repository demonstrates a common JavaScript bug involving incorrect null handling in a simple addition function.

## Bug Description

The `foo` function is designed to add two numbers. However, its null handling is flawed. It returns 0 if either input is null, even if the other input is a valid number.  This is likely not the intended behavior.

## Bug Solution

The solution file provides an improved version of the function that handles null values more appropriately. It checks for null values and provides a default value or throws an error depending on the requirement.

## How to Run

1. Clone the repository.
2. Open `bug.js` to see the buggy code and `bugSolution.js` to see the corrected code.
3. Run the JavaScript files in your preferred environment (e.g., Node.js, browser console).