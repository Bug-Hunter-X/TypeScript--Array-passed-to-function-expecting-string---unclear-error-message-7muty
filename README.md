# TypeScript: Array passed to function expecting string

This repository demonstrates a common TypeScript error where an array is passed to a function expecting a string. The error message can sometimes be unclear, making it difficult to debug.

## Bug
The `bug.ts` file contains a function `greeter` that expects a string.  However, an array is passed to it. TypeScript will throw an error, but the exact nature of the error might not immediately point to the type mismatch.

## Solution
The `bugSolution.ts` file demonstrates two ways to fix this issue:

1. Change the function signature to accept an array of strings.
2. Pass a single string to the function.