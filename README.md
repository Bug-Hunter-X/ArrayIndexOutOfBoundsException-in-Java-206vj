# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The `Bug.java` file contains code that attempts to access an array element outside its valid range.  The `BugSolution.java` file provides a corrected version.

The error is caused by the fact that Java arrays are zero-indexed. Therefore, an array of size 5 has valid indices from 0 to 4.  Attempting to access index 5 results in an exception.

This example highlights the importance of careful array index checking in Java to avoid runtime errors.