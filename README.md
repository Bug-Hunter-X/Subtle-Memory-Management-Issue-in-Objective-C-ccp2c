# Objective-C Memory Management Bug

This repository demonstrates a common and subtle memory management bug in Objective-C related to string handling.  The bug involves improper handling of string ownership, potentially leading to crashes or memory leaks.  The solution showcases the correct approach to avoid this issue.

## Bug Description
The `bug.m` file contains code that incorrectly manages the ownership of an NSString object. This leads to either premature deallocation (causing crashes) or memory leaks if the string is not properly released.

## Solution
The `bugSolution.m` file provides a corrected version of the code. The solution ensures proper object ownership and lifecycle management, preventing memory issues.

## How to Reproduce
1. Clone this repository.
2. Open the project in Xcode.
3. Run the code in `bug.m` and observe the potential crash or unexpected behavior.
4. Run the code in `bugSolution.m` to see the correct implementation.