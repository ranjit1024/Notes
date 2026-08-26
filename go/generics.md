a typed parameter is called generic 
for example you a function that you have a function that take int and you want ot make a fucntion that take pratermeter float64 so you have to write a another fucntoin with different function insted of that you create functin take takes type as a placeholder and can take anything as a parameter that is whar we called typed parameter


```go
func SliceIndex[S ~[]E, E comparanel](s S, v E)int{
    
}

```

~ this symbol is nutorius part the thing is that this symbol represent the any type that underlaying type is []E which is E type is comparable 