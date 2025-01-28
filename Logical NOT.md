!expression returns true if expression is false. 

```
!null
>true

! (0===0)
> false

!(3 <= 4) 
> false

!false
> true
```


Another example:
```
const firstName = prompt("Enter your first name");

if(!firstName){
firstName = prompt("Try again!");
}
```

Another more complicated example:

```
const age = 8;

if (!(age >= 0 && age < 5 || age >= 65)) {
console.log("You are not a baby or a senior!")
}
```

