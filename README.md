# TypeScript Type Error: Pushing String into Number Array

This repository demonstrates a common type error in TypeScript that occurs when attempting to add an element of an incorrect type to an array.

The `bug.ts` file contains the erroneous code.  The `bugSolution.ts` file provides a corrected version.

The error is caused by attempting to add a string to an array that is explicitly typed as a number array. TypeScript's type system prevents this to maintain type safety.  The solution involves ensuring only numbers are added to the array.