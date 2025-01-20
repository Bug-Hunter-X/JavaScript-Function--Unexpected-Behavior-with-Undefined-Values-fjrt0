# JavaScript Function: Unexpected Behavior with Undefined Values

This repository demonstrates a common JavaScript bug related to handling undefined values in a function. The function `foo` correctly handles null values but fails to gracefully manage undefined parameters.

## Bug Description

The `foo` function adds two numbers. It correctly handles null values by returning null if either input is null. However, it doesn't explicitly handle undefined values, which can lead to unexpected results (NaN or errors).

## Solution

The solution involves adding checks for undefined values in addition to null checks. This improves the function's robustness and prevents unexpected results.

## How to reproduce the bug

1. Clone this repository.
2. Run the `bug.js` file (e.g., using Node.js: `node bug.js`).
3. Observe the output; undefined values will likely not produce the expected result.