# Array vs Slice

**array**: 
- Array is static it cannot to grow as per need 

**Slice**
- An abstration over array that counts for a len and cap if cap exceeds then create new array then the reference of old array is eligible for GC 
slices are go answer to how to handel dynamic array

1. The way it is works it has a struct called acural data and 

go
```
struct slice { 
    data;
    len int;
    capacity int
}
```
 if cap(execeds) then crate a new array and then copy existing data 
 if not just add the data 


this is almost basic for any dunamic array 

be it 
-> C++ vector 

no idea about python 