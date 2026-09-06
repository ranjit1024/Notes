# Goroutines

In Go, we can run multiple functions concurrently by using goroutines.

A goroutine is a lightweight unit of execution managed by the Go runtime. It can execute a function concurrently with other goroutines, including the `main` goroutine.

A goroutine is independent of the function that started it, but it cannot outlive the Go program. When `main()` returns, the program exits, and any goroutines that are still running are terminated.


# WaitGroups 

it golang we dont have an option for like if main fucnttin execucatio happen every fast then we dont have an time to run the goroutine so we use someing called waitgroup where we say will till all teh goroutines run concurrly and the go to the next section 
