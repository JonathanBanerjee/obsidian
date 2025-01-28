Every string has a set of methods. They are built-in actions that can perform with individual strings. 

This includes things like:
Searching with a string.
Replacing part of a string.
Changing the casing of a string. 

There is a difference between parenthesis and no parenthesis. If we add parenthesis, we are executing a method. 

e.g. 
let msg = "leave me alone right now i hate you plz"
msg.toUpperCase();
>"LEAVE ME ALONE RIGHT NOW I HATE YOU PLZ"

This is new string, and therefore is not destructive. The original message is can still be called using msg. 

You can store the uppercase version as a variable by doing:
let angryMsg = msg.toUpperCase();


Using trim, it removes blank spaces on the left and right. 
let greeting = ' leave me alone plz' ;
greeting.trim() // 'leave me alone plz'


You can chain methods together. 
let greeting =" Hello again!!!        "
greeting.trim().toUpperCase()
>"HELLO AGAIN!!!"

