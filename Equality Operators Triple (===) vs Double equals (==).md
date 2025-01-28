
## Double Equals  
Checks for equality of value but not equality of type. 
It coerces both values to the same type and then compares them.

```
//Weirdness of double equals 

true == false; //false 
7=="7"; //true
0 == false; //true
null == undefined; //true
```

## Not equal  (double)
```
1 != 2; // true
1 != "1"; //false
```


## Triple Equals
This does care about type. It will not coerce another value to another type. 
```
1 === "1"; //false
```

## Not equal (Triple)
```
1 !== '1'; //true
```

Rule of thumb: Always use triple equals when comparing things. Unless you have a deep understanding of using double equals. 