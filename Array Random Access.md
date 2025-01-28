Each element has a corresponding index, starting at 0. 

```
let days = ["Monday", "Tuesday", "Wednesday"]

days[0]

> Monday

```

The length is always 1 greater than the maximum index!
See the max index using the array above is 2.
```
days.length
>3 
```


Other things of note:
```
days[30]
> undefined

days[1][0]
> T
```


Modifying arrays:
```
let colors ["rad", "orange", "green", "yellow"];

colors[0] = "red";
colors[2] = "yellow";
colors [3] = "green";

colors[4]; =
> undefined
colors[4] = "blue";
> ["red", "orange", "yellow", "green", "blue"];
```