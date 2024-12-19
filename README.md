# TypeScript Type Error Bug

This repository demonstrates a common type error in TypeScript: attempting to perform an operation on incompatible types.  The file `bug.ts` contains the erroneous code, while `bugSolution.ts` provides the corrected version.

## Bug Description
The `add` function is defined to accept two numbers and return their sum. However, the code attempts to call it with a number and a string, which results in a type error.