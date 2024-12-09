# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of MongoDB's `$inc` operator. The `$inc` operator is designed to increment numeric fields, and providing a string value results in an error.

## Bug Report
The code attempts to increment the `age` field by '1', which is a string, resulting in a MongoDB error.  The correct usage requires an integer or a number.

## Solution
Use an integer to increment the field value using the `$inc` operator to properly update the document.
