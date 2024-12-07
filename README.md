# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The error arises from providing a string value instead of a numerical value to the `$inc` operator, leading to unexpected results. The solution shows the correct usage of the operator.

## Bug Description:
Incorrectly using the `$inc` operator with a string value will lead to either a failed query or an incorrect result in the database.

## Solution:
The solution involves replacing the string value with a numerical value in the `$inc` operator.