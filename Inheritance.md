You can see inside the dev tools where an element has been inherited from. 

```
form {
color: greenyellow;
}

  

button,
input {
color: inherit;
}
```

The button and input elements are selected to inherit from the nearest parent that has a colour. 

You can check on the MDN docs whether an element can be inherited or not. For example, border can't, but color can. 