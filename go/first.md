## Go Lang

- Map 
   > Map in go Lang is a associative data type 
   is stores data in key value form not in a array where it is on index based
   ```
   package main
   import (
      "fmt"
   )
   func main() {
      fmt.Println("Data")
      m := make(map[string]int)
      m["ranjit"] = 12
      fmt.Println(m)
   }```****

- _, for go this is veriable but ignore it
  
>  Function 

this is a function for in GO this is a function taking  ***int*** and retturn and ***int*** 
> 
```
package main

import "fmt"

```func plus(a int, b int) int {
	if a == 12 && b == 12 {
		return a * b
	}
	return a + b
}
func main() {
	res := plus(12, 12)

	fmt.Println(res)
	fmt.Println("fad")
} 
```
