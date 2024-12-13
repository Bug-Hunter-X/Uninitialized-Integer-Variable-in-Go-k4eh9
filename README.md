# Uninitialized Integer Variable in Go

This example demonstrates a common error in Go: printing the value of an uninitialized integer variable.  Go doesn't automatically initialize variables to 0; they start with whatever data happens to be in the allocated memory location. This leads to unpredictable behavior.

**bug.go** shows the problem. The solution, **bugSolution.go**, shows how to explicitly initialize the variable to zero.