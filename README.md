# MongoDB $inc Operator with String Values

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field by a specified value, but using a string instead of a number will lead to unexpected results.  The code shows the erroneous use of a string with `$inc` and a corrected version demonstrating the correct usage.

## Bug
The original code incorrectly uses a string '1' instead of the number 1 with the `$inc` operator. This causes the string to be appended to the field value instead of incrementing it. 

## Solution
The corrected version uses the number 1 as the increment value, resulting in the correct numerical increment.
