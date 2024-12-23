# Unexpected Type Coercion in JavaScript
This example demonstrates a common JavaScript pitfall: unexpected type coercion due to loose typing.  The function `foo` attempts to add two values, but because one is a string, JavaScript performs string concatenation instead of numerical addition. This can lead to subtle and difficult-to-debug errors.

The solution shows how to explicitly type check or use `parseInt` to ensure that only numerical addition happens. 