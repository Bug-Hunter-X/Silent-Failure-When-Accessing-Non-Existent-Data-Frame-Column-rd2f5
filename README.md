# R Bug: Silent Failure with Non-Existent Data Frame Column

This repository demonstrates a common yet subtle bug in R: silently failing when attempting to access a non-existent column in a data frame.  The code executes without throwing an error, but produces unexpected `NA` values, which can be difficult to debug.

The `bug.R` file contains the buggy code.  The `bugSolution.R` file offers a solution using proper error handling.