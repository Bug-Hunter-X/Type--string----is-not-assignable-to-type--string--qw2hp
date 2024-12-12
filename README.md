# Type 'string[]' is not assignable to type 'string'

This repo demonstrates a common TypeScript error: passing an array to a function expecting a string.  The `greeter` function expects a single string, but an array is provided causing a type error.  The solution shows how to correctly handle this by either modifying the function signature or iterating through the array.