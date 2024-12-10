# Haskell `undefined` Gotcha

This repository demonstrates a subtle runtime error that can occur in Haskell when using the `undefined` value with the `fromMaybe` function.  The code compiles without warnings, but execution results in a runtime exception. The solution shows how to handle this situation gracefully.

The `bug.hs` file contains the problematic code. The `bugSolution.hs` file provides a corrected version. 