# R's Silent Subsetting Failure: Empty DataFrame Instead of Error

This repository demonstrates a subtle yet potentially problematic behavior in R when subsetting data frames.  When using the `%in%` operator with character vectors containing values not present in the data frame's column, R silently returns an empty data frame instead of throwing an error or warning. This can lead to unexpected behavior and difficult-to-debug issues.

The `bug.r` file shows the problematic code, while `bugSolution.r` provides a solution to mitigate this behavior.
