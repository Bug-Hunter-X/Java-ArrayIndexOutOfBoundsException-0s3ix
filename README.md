# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`. The `Bug.java` file contains code that attempts to access an array element beyond its valid index range, leading to this exception.  The solution, `BugSolution.java`, corrects this error by adjusting the loop condition to avoid out-of-bounds access. This is a fundamental bug to be aware of when working with arrays in Java.

## How to Reproduce

1. Compile `Bug.java` using a Java compiler (javac Bug.java).
2. Run the compiled code (java Bug).
3. Observe the `ArrayIndexOutOfBoundsException` being thrown.