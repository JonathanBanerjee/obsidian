
#### Flex Basis
Flex-basis decides the size of an element before it's placed in (the starting point).
Flex-basis is along the main axis, so it can be a width or a height depending on where the main axis is. 

```
#container {
background-color: #003049;
width: 90%;
/* height: 500px; */
margin: 0 auto;
border: 5px solid #003049;
display: flex;
flex-direction: column;
justify-content: center;
flex-wrap: wrap;
}

  
#container div {
width: 200px;
height: 200px;
text-align: center;
flex-basis: 400px;
}
```


#### Flex Grow
Controls the amount of available space an element should take up. It accepts a unit-less number value. 

```
#container {
background-color: #003049;
width: 90%;
/* height: 500px; */
margin: 0 auto;
border: 5px solid #003049;
display: flex;
flex-direction: row;
justify-content: center;
flex-wrap: wrap;
}

  
#container div {
width: 200px;
height: 200px;
text-align: center;
flex-basis: 200px;
}

  

div:nth-last-of-type(1) {
flex-grow: 1;
}
```
