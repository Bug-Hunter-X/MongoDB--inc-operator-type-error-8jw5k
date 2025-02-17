# MongoDB $inc Operator Type Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The error arises from providing a string value instead of a numeric value to increment a field.

## Bug
The original code attempts to increment the `counter` field by "1" (a string), which is not a valid operation for `$inc`.

## Solution
The corrected code increments the `counter` field by 1 (a number), which correctly updates the document.