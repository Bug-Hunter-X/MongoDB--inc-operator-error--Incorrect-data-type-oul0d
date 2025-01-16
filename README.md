# MongoDB $inc Operator Error: Incorrect Data Type

This example demonstrates an error that can occur when using the MongoDB `$inc` operator. The `$inc` operator is used to increment a numeric field by a specified value. Attempting to increment a field that is not a number results in an error.  This example shows the error and provides the correct solution.

**Bug:** Incorrect usage of the `$inc` operator. The field is treated as a string instead of a number.

**Solution:** Ensure the field to be incremented is a number (integer or double).