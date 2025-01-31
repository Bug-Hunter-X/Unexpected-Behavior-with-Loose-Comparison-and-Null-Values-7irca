# JavaScript Bug: Loose Comparison and Null Values

This repository demonstrates a common JavaScript bug involving loose comparison (==) and the handling of null values.  The bug arises from the fact that JavaScript's loose comparison can lead to unexpected behavior when comparing values with null or undefined.

## Bug Description
The provided `foo` function attempts to add two numbers together and handle the case where either input is null.  The original implementation uses loose comparison to check for null.  However, this is problematic since loose comparison can produce unexpected results in various situations.