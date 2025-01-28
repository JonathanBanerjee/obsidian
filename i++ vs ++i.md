
i++ is the post increment operator. It returns the current value of the variable and then increments it.

let i = 0;
i++ = 0;

Note that it returns the value prior to the increment. However, if you type i again in the console, it will return 1. 

Another example of this:

let i = 5;
let result = i++;
result 
> 5

i 
> 6



++i  is the pre-fix or pre increment operator. It increments the variables value by 1 first, and then returns the value. 

e.g. let i = 0
++i
> 1

let i = 5
let result  = ++i 
result 
> 6

