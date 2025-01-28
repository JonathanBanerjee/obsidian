
Else makes is the last condition, i.e. if nothing else was true along this journey, then do this:

For example:

```
let rating = -99;

if (rating === 3){
console.log("You are a superstar!");
}
else if (rating ===2) {
console.log("Meets expectations");
}
else if (rating ===1) {
console.log("Needs Improvement");
}
else {
console.log("Invalid rating");
}
```

For the days of the week

```
const dayOfWeek = prompt("enter a day").toLowerCase();

if(dayOfWeek === 'monday'){
console.log("Ughh I hate Mondays!");
}
else if (dayOfWeek === "saturday"){
console.log("Yay I love Saturdays!")
}
else if (dayOfWeek === "friday"){
console.log("Fridays are decent, especially after work!")
}
else {
console.log("meh");
}
```


Another example:
```
let random = Math.random();
if(random < 0.5){
console.log("Your number is less than 0.5!")
}
else {
console.log("Your number is greater  (or equal) than 0.5!");
}
console.log(random);
```

One more example:

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
else{
console.log("You are a senior. You pay $10")
}
```