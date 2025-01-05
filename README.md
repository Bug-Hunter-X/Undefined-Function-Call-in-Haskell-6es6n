# Haskell Undefined Function Bug

This repository demonstrates a simple but common error in Haskell: calling an undefined function.  The `bug.hs` file contains the buggy code, which attempts to call a function that doesn't exist. The `bugSolution.hs` file shows the corrected version.

## How to Reproduce

1. Clone this repository.
2. Compile `bug.hs` using a Haskell compiler (like GHC): `ghc bug.hs`
3. Observe the compiler error indicating the undefined function.
4. Compile and run `bugSolution.hs` to see the corrected behavior.

## Lesson Learned

Always ensure that all functions you call are properly defined within the scope of your program, either by importing them from a module or defining them locally.