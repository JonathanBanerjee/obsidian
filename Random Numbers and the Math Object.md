
The Math Object contains properties and methods for mathematical constants and functions. E.g. Math.E for Eulers number.


We have method for:
rounding:
e.g. Math.round (4.9) //5

Absolute Value:
Math.abs(-456) //456

Powers:
//Raises 2 to the 5th Power.
Math.pow(2,5) //32

//Removes decimal (floor):
Math.floor(3.9999) //3

// Rounding up no matter what (Ceil):
Math.ceil(24.4)  //25

We have constants like PI:
Math.PI //3.14159.....

Math is there in the console.

You can type "Math" in the console and hit enter. 
It will then display the Math object. 


Random Numbers
Math.random() gives us a random decimal between 0 and 1 (non-inclusive).

Math.random()
You'll get a different but very long decimal. 

In order to get a whole number, you will either need to ceil or floor it.

```
const step1 = Math.random();
const step2 = step1 * 10
const step3 = Math.floor(step2);
const step4 = step3 + 1;

Math.floor(Math.random() + 10) + 1;
```