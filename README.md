# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a specified value. However, in the example provided, a string value ('1') is provided instead of a number (1). This results in an error.

## Bug
The bug lies in the incorrect usage of the `$inc` operator. The value to increment by must be a number. Using a string value will lead to an error.

## Solution
The solution involves providing a numeric value to the `$inc` operator, correcting the update operation.
