- All JS values have an inherent truthyness or falsyness about them.
- Falsy values: false, 0, "" (empty string), null, undefined, NaN.
- Everything else is truthy!


Example:
```
const userInput = prompt("Enter something");

if(userInput){
console.log("truthy!")
}
else {
console.log("Falsy!")
}
```

Another example:

```
if(0){
console.log("truthy!")
}
else {
console.log("Falsy!")
}
```