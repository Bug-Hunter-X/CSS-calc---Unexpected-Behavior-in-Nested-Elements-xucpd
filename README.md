# CSS calc() Unexpected Behavior

This repository demonstrates a common issue with CSS's `calc()` function when dealing with percentages and pixels in nested elements. The issue arises from the way `calc()` resolves percentage values, which can lead to unexpected results.

## Bug Report

The bug is demonstrated in `bug.css`.  A simple layout with a container and an inner element shows that the width of the inner element calculated by `calc()` does not behave as expected due to the nested context.

## Solution

The solution, found in `bugSolution.css`, addresses this by ensuring the percentages are calculated correctly in the nested context.  More explicit unit usage and proper understanding of the order of calculations resolve the issue.  Refer to the comments within `bugSolution.css` for a detailed explanation.