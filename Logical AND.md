1 <= 4 && 'a' === 'a' //true


```
true && true
> true

true && false
> false

false && true
> false

false && false
> false

```


A better example:

```
const password = prompt("Enter your password");

if(password.length >= 6 && password.indexOf(' ')=== -1){
console.log("Valid password!")
}
else {
console.log("Incorrect password format!");
}
```