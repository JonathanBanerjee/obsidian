Keyword added to a selector that lets you style a particular part of selected elements(s)

::after

::before

::first-letter - This will change the first letter of an element, for example this will change the first letter of every h2 element:
```
h2::first-letter {
font-size: 50px;
}
```

::first-line 
```
p::first-line {
color: purple;
}
```

::selection - This will change the colour of a paragraph when you highlight over it:
```
p::selection {
background-color: #fcbf49;
}
```