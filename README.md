# Unexpected Behavior with Null Values in JavaScript

This example demonstrates an uncommon JavaScript bug related to loose comparison and null values.  The `foo` function adds two numbers.  However, the loose comparison (`==`) in the `if` statement can yield unexpected results when dealing with null values.

## Bug Description
The issue arises from JavaScript's loose equality (`==`). This can lead to unexpected behavior when dealing with null values in the context of mathematical operations.

## Solution
The solution involves explicit null checks using strict equality (`===`) or a similar approach, thereby ensuring that null values are properly handled in the function's logic, preventing unexpected results. 

## How to reproduce
1. Copy and paste the `bug.js` content into a JavaScript file.
2. Run the file in a JavaScript environment.
3. Observe the output which shows unexpected results when using null values.
4.  Then copy and paste the `bugSolution.js` code to see the explicit null handling.