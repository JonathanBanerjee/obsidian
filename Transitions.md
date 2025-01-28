Allow us to animate the transition from one property value to another property value.

A simple example:
```
.circle {
width: 300px;
height: 300px;
background-color: magenta;
transition: 1s;
}

.circle:hover {
background-color: cyan;
border-radius: 50%;
}
```


#### Transitions
These can enable you to specify the property name, duration, timing function and delay. 

It is possible to single a property out, e.g:
`transition: background-color 3s;`

To add a delay
It is possible to add a delay and this can be done to all properties e.g:
`transition: all 1s 1s;`


##### Timing functions
```
div:nth-of-type(1) {
transition-timing-function: ease-in;
}

div:nth-of-type(2) {
transition-timing-function: ease-out;
}

div:nth-of-type(3) {
transition-timing-function: cubic-bezier(0.7, 0, 0.84, 0);
}

div:nth-of-type(4) {
transition-timing-function: cubic-bezier(0.85, 0, 0.15, 1);
}
```
https://easings.net


For example, the full thing can be:
```
transition: background-color 1s, ease-in, border-radius 2s;
```
