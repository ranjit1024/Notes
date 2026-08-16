# String and rune

string and the problem it solves

**How Go think about string**

i go strings are collection of bytes no one thing not every thingg is a only one byte

for example 

a => 1 byte 

and `Emoji` is not a one byute

so if you have something like a `Remoji` then it is not a 2 bytes it is 4 bytes it is not a right representation of a sting lenght 

### That is the probelm rune solves

rune is actual `Unicode code point` that gives the some code to the the acual char 

here we dont dont care about the `UTF-8` so care acout `Unicode code point`
for taht char 


# rune = int32