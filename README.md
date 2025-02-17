# Go Race Condition Example
This repository demonstrates a race condition in Go.  The `bug.go` file contains code that attempts to increment a counter in multiple goroutines without proper synchronization. This can result in incorrect final values.

The `bugSolution.go` file shows a corrected version using a mutex to protect the shared variable and prevent the race condition.

This example highlights the importance of using synchronization primitives such as mutexes or atomic operations when dealing with shared resources in concurrent Go programs.