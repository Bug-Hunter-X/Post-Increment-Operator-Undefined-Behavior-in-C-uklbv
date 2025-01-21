# Post-Increment Operator Undefined Behavior in C
This repository demonstrates an example of undefined behavior in C related to the post-increment operator.
The `bug.c` file contains code that exhibits this behavior. The `bugSolution.c` file offers a corrected version.
The issue arises from modifying the value of `x` multiple times within a single expression without any sequence points. Therefore, the output is unpredictable.