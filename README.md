# Inconsistent Width Calculation with calc() in Flexbox

This repository demonstrates an uncommon issue encountered when using the `calc()` function with percentage and fixed values within a flexbox container.  The issue lies in the potential for inaccuracies in width calculations due to rounding errors and the way `calc()` interacts with percentage units in flexible layouts.

The `bug.css` file contains the problematic code, and `bugSolution.css` shows a solution that uses a more robust approach to achieve consistent width calculations.