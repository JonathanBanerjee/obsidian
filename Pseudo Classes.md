Keyword added to a selector that specifies a special state of the selected elements:

:active - represents an element (such as a button) that is being activated by the user. The "activation" starts when the user presses down the primary mouse button.
```
.post button:active {
background-color: #02c39a;
}
```

:checked - enables you to select any radio buttons or checked boxes that are checked. 

:first

:first-child

:hover - This will change what displays when the mouse is hovered over an element:
```
button:hover {
background-color: #e63946;
color: #f1faee;
}
```

:not()

:nth-child()

:nth-of-type() - Enables you to select the position in a group of siblings. The code below changes every 2nd element to the colour specified.
```
.post:nth-of-type(2n) {

background-color: #dfe8dc;

}
```