# Incorrect Use of $inc operator in MongoDB Update Operation
This example demonstrates an error in using the `$inc` operator in MongoDB update operations.  The error stems from providing a string value instead of a numeric value to the `$inc` operator.

**Problem:** Incorrect data type provided to `$inc`.  The `$inc` operator expects a numeric value to increment a field. Providing a string results in unexpected behavior or an error.

**Solution:** Always provide numeric values to `$inc` to ensure proper increment behavior. 

This repository includes the problematic code (`bug.js`) and the corrected code (`bugSolution.js`).