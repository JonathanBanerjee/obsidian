If not the first thing, maybe this other thing?

```
let rating = 2;

if (rating === 3){
console.log("you are a superstar!")
}
else if (rating === 2){
console.log("meets expectations");
}
```

Another example and can be chained:
```
const dayOfWeek = "Friday";

if(dayOfWeek === 'Monday'){
console.log("Ughh I hate Mondays!");
}
else if (dayOfWeek === "Saturday"){
console.log("Yay I love Saturdays!")
}
else if (dayOfWeek === "Friday"){
console.log("Fridays are decent, especially after work!")
}
```


Else-if's have to come after an if or another else-if:
```
// 0-5 - Free
// 5-10 Child $10
// 10 - 65 Adult $20
// 65+ Senior $10

const age = 8;
if (age < 5) {
console.log("You are a baby, you're in for free")
} 
else if (age < 10){
console.log("You are a child, you pay $10")
} else if (age < 65) {
console.log("You are an adult you pay $20")
} 
```