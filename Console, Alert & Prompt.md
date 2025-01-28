
console.log() prints arguments to the console.
You can pass in multiple arguments. 

console is also an object, so there are many methods attached to it. 
e.g. console.error("aerrr"); //prints it in red.

alert() prints out to the user, but not in the console. It adds a pop up. 
```
alert("HI There");
//this pops up on screen.
```

prompt()  asks the user to enter something.
```
prompt("Please enter a number");
//a popup asks a user to enter a number.
```

You can also do:
```
let userInput = prompt("Please enter a number");
userInput
"97"

//Note this comes as a string, so you will need to use parseInt() if you want to change it to a number for operations.
parseInt(userInput)
97
```
