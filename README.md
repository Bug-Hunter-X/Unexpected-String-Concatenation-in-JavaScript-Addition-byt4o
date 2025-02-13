# Unexpected String Concatenation in JavaScript Addition

This example demonstrates a common error in JavaScript where loose typing leads to unexpected string concatenation instead of numerical addition.  The `add` function attempts to add two values, but if one is a string, JavaScript will perform string concatenation.

**Bug:** The `add` function incorrectly concatenates the number 5 and the string '5' instead of adding them numerically. 

**Solution:** The solution is to explicitly convert both parameters to numbers before performing addition using `Number()` or `parseInt()`.