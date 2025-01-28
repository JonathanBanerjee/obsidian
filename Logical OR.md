These use two pipe characters || 

Example:

```
// Only one side needs to be true!

1 !== || 10 === 10 
> true

10/2 === 5 || null 
> true

0 || undefined 
> false
```

Using only logic:
```
true || true
> true

true || false
> true

false || true
> true

false || false
> false

```

Another example:

```
// 0-5 - Free
// 5-10 Child $10
// 10 - 65 Adult $20
// 65+ Senior $10

const age = 90;
if(age >= 0 && < 5 || age >= 65) {
console.log ("FREE");
} else if (age >= 5 && age < 10) {
console.log("$10")
} else if (age >= 10 && age < 65) {
console.log("$20")
} else {
console.log("Invalid age");
}
```

And has precedence over Or (And runs first). 