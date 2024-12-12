# Freeing Stack-Allocated Memory in C
This example demonstrates a common error in C programming: attempting to free memory that was not allocated using malloc(), calloc(), or similar functions.  In C, variables declared on the stack are automatically managed and deallocated when they go out of scope. Using `free()` on such variables results in undefined behavior.

The `bug.c` file contains the erroneous code, while `bugSolution.c` shows the correct approach. 