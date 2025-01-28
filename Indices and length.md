Strings are indexed. Every character that belongs in a string has a corresponding positional number. 

let animal = "Dumbo Octopous"

This will access the zeroth character. 
animal[0]
> "D"

animal[6]
>"O" 


let phone = "(231)345-1234"

The first index can be used to determine what type of phone number it is. 

.length 
animal.length 
This is the number of characters
> 13 

Note this is not the highest index of the string. in the case of Dumbo Octopus above, the S has an index of 12. 

Adding strings together (concatenation)
"lol" + "lol"
>"lollol"


```
let firstName = "River";
let lastName = "Phoenix";

firstName + lastName 
"RiverPhoenix"

firstName 
"River"

lastName
"Phoenix"
```

It is not possible to update one character at a time in a string. 

e.g. firstName = "river" -- this is a completely new string. 

To add a space:
firstName + " " + lastName
"River Phoenix"

Assigning it to a variable:
let fullName = firstName + " " + lastName


Coercion:
let result = 1 + "hi"
result 
> "1hi"

typeof result
>"string"

typeof 1
>"number"