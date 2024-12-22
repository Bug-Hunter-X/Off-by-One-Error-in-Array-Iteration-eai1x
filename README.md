# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays. The error arises from an incorrect loop condition that causes an attempt to access an index beyond the array's bounds, leading to an `ArrayIndexOutOfBoundsException`.

The `bug.java` file contains the erroneous code, while `bugSolution.java` presents the corrected version.

This is a simple example but showcases a subtle error that can be difficult to spot in larger codebases.  Always carefully check your loop conditions and array indices to prevent this type of issue. 