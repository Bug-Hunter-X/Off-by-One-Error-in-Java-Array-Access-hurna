# Off-by-One Error in Java Array Access

This repository demonstrates a common off-by-one error in Java when accessing array elements.  The error occurs because the loop condition `i <= array.length` attempts to access an index beyond the array's valid range (0 to array.length-1).

The `Bug.java` file contains the erroneous code, while `Solution.java` provides the corrected version.

This example highlights the importance of careful array indexing in Java to prevent runtime exceptions.