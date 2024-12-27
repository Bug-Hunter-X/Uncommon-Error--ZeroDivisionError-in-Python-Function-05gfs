# Uncommon Error: ZeroDivisionError in Python
This repository demonstrates a subtle error in Python function handling that can lead to a ZeroDivisionError. The function is designed to handle division by zero in some cases, but misses a key scenario.
## Problem Description
The Python function `function_with_uncommon_error` aims to handle division by zero by returning the other operand if either `a` or `b` is zero. However, it fails when both `a` and `b` are zero, resulting in a `ZeroDivisionError`. This error is less commonly encountered than simple division by zero, as the function only attempts to divide if neither `a` nor `b` is zero.
## Solution
To fix the issue, we need to include an explicit check to handle the case where both `a` and `b` are zero, returning an appropriate value (or raising a more informative custom exception).