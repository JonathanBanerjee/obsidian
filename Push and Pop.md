Push - Add to end.
Pop - Remove from end.



```
let movieLine ["tom", "nancy"];

movieLine.push("oliver")

movieLine 
> ["tom", "nancy", "oliver"];

```

Note: When you push onto arrays, the array is actually updated  but string methods are not:

```
let cat = "blue";
cat.toUpperCase()
> BLUE
cat
> blue

movieLine.push("eva")
> 4
movieLine
> ["tom", "nancy", "oliver", "eva"];


//You can add multiple arguments too:

movieLine.push("harry", "hermione")
> 6
movieLine
> ["tom", "nancy", "oliver", "eva", "harry", "hermione"];
```

Using pop:
Pop does not require any arguments

```
movieLine.pop()
> "hermione"

let person = movieLine.pop();
person
> "Harry"
```