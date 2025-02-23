# Missing Argument Label in Swift Function Call

This repository demonstrates a common error in Swift: forgetting to include argument labels when calling a function.

## Bug

The `calculateArea` function is defined with explicit argument labels (`width:` and `height:`).  However, the second call to the function omits the label for the `height` argument.  This results in a compiler error.

## Solution

The solution is simply to include the argument labels in the function call.