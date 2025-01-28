The switch statement is another control-flow statement that can replace multiple if statements.
See the "default case" as an "else" block.
See 6 & 7 below, that is how you link them to the same block of code (E.g. Sat and Sunday are the weekend).

For example:
```

const day = 4;

switch(day) {
case 1: 
	console.log("Monday");
break;
case 2: 
	console.log("Tuesday");
break;
case 3: 
	console.log("Wednesday");
	break;
case 4: 
	console.log("Thursday");
	break;
case 5: 
	console.log("Friday");
	break;
case 6:
case 7:
	console.log("Weekend");
	break;
default:
 console.log("I don't know that!");
}

```