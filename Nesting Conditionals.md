This enables you to search for a specific criteria, for example with a password:


```
// Password must be 6+ characters.
// Password cannot include spaces.

const password = prompt("please enter a new password");

if(password.length >= 6){
console.log("Long Enough password!")
}
else{ 
console.log("Password too short! Must be 6+ characters!")
}

if (password.indexOf(' ') === -1) {
console.log("Good job! No space!")
}
else {
console.log("Your password contains spaces, please remove them!")
}
```


Here's how you nest it:

```
// Password must be 6+ characters.
// Password cannot include spaces.

const password = prompt("please enter a new password");

if(password.length >= 6){
	if (password.indexOf(' ') === -1) {
	console.log("Valid Password!")
	}
	else {
	console.log("Your password cannot contain spaces")
	} 
}
else{ 
console.log("Password too short! Must be 6+ characters!")
}


```