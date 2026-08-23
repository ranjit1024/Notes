# go does not have any emum as a premative data type

enums is a type that has a fixed number of possibel values 

in go tipicaly enums are achinced by const and iota 


go```
package main

import "fmt"

type status int

const (
	Pending status = iota
	Running status = iota
	Completed
	Failed
)

func main() {
	fmt.Println("fadsfa")
	fmt.Println(s)
}
```