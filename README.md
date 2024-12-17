# Uncommon CSS `calc()` Errors

This repository demonstrates some uncommon errors related to the CSS `calc()` function.  The `calc()` function, while powerful, can produce unexpected results when used improperly, especially when mixing percentage and fixed units or within media queries.  The `bug.css` file shows examples of problematic code, while `bugSolution.css` presents solutions for these issues.

**Issues:**

* Unexpected results when combining percentages and fixed units (px, em, etc.) within a single `calc()` expression.
* Inconsistent behavior across browsers when using `calc()` within media queries.

**Solutions:**

The solutions often involve either avoiding the use of mixed units in `calc()` expressions or employing alternative techniques to achieve the desired layout or styling.