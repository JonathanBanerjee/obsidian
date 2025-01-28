Arguments are inputs that can be passed into the method to alter how they behave. 

For example:
"haha that is so funny!".indexOf("h")
>0

"haha that is so funny!".indexOf("!")
>21


// & is not present.
"haha that is so funny!".indexOf("&")
> -1

This is commonly used to test if a string contains something. 

.slice() is another method that can take arguments and can take more than one argument.
It is used to extract or slice a portion of a string. 
It returns it as a new string. 
The arguments we give it are the two indices we want to slice our string from. 
If the index is in brackets in the documentation, this means it's optional, for example the endIndex in slice is optional. 

You can use negative characters as well - it works backwards from the end. 

e.g. msg.slice(-6);
"funny!"

It does not impact the original string, it gives us a copy or new string instead.

Replace() 

msg
> "haha that is so funny!"

msg.replace("haha", "lololololol")
>"lololololol that is so funny!"

Note: It will only do it on the first instance. 
e.g. msg.replace("h", "H");
>"Haha that is so funny!"

However, there is a replaceAll() method to replace all the instances but note that it is not implemented in most browsers at this point. 

repeat()
"lol".repeat(3)
"lollollol"
The original string like always is unchanged.