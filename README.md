# Loose Equality and Null Values in JavaScript Addition

This repository demonstrates a common JavaScript bug related to loose equality (==) and null values in addition operations.  The `bug.js` file contains the faulty code, while `bugSolution.js` provides the corrected version.

## Bug Description

The original code uses loose equality (==) to check for null values before performing addition. This approach can lead to incorrect results because loose equality performs type coercion, which can produce unexpected outcomes when comparing null with other data types (such as numbers or strings).

## Solution

The solution uses strict equality (===) to reliably check for null values. Strict equality does not perform type coercion, providing a more accurate and reliable way to handle null values in the addition operation.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js` and observe the problematic use of loose equality.
3. Open `bugSolution.js` and see how the issue is resolved by using strict equality.
4. Run both files to see the difference in the output.
