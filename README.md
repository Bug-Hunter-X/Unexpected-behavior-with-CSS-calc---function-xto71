# Unexpected behavior with CSS calc() function
This repository demonstrates a subtle bug related to the CSS `calc()` function. The bug arises from the use of unnecessary spaces around operators and the omission of units in the calculation.

## Bug Description
The `calc()` function in CSS is used for performing calculations within CSS properties.  However, improper spacing around operators and the absence of units can lead to unexpected or incorrect results. This can be hard to debug as the error messages are not always clear.

## Bug Solution
The solution involves carefully removing unnecessary spaces from around the operators and ensuring that all numeric values include their appropriate units (e.g., `px`, `em`, `%`, etc.).

## How to reproduce
1. Clone this repository
2. Open `bug.css` to see incorrect usage of calc()
3. Open `bugSolution.css` to see the corrected usage of calc()