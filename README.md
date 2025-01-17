# ActionScript Null Object Reference Bug

This repository demonstrates a common error in ActionScript: attempting to access a property of a null object.  The `bug.as` file contains the erroneous code, which throws a `NullPointerException`. The `bugSolution.as` file provides a corrected version that handles null objects gracefully.

## How to Reproduce

1. Open `bug.as` in an ActionScript editor.
2. Compile and run the code. You should encounter a `NullPointerException`. 

## Solution

The `bugSolution.as` file shows the corrected code, which incorporates a null check before accessing the object's property, avoiding the error. This demonstrates the importance of error handling and defensive programming in ActionScript.