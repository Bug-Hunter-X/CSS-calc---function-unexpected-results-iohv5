# CSS Calc() Function Unexpected Results

This repository demonstrates an issue with the CSS `calc()` function where unexpected results occur when using percentages and other units together.  The problem arises when the parent element's size is not explicitly defined or is also calculated, leading to incorrect width or height calculations by `calc()`. The solution showcases how to properly structure your CSS and ensure consistent calculations.

## Bug Report

The `bug.css` file demonstrates the erroneous calculation using `calc()`.  Observe how the calculated width does not align with expectations. 

## Solution

The `bugSolution.css` file presents a modified approach that solves the problem, providing a clear example of how to ensure correct calculations by the `calc()` function. 

## How to Reproduce

1. Clone this repository.
2. Open `index.html` in your web browser.  Note the incorrect width of the element in the first example.
3. Inspect the second example to see the corrected calculation.