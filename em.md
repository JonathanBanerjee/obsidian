Em's are relative units.

With font-size, 1em equals the font-size of the parents. 2em's is twice the font-size of the parent etc.

With other properties, 1em is equal to the computed font-size of the element itself. 

These are very useful for when it comes to scaling, for example, this button will always be relative to the parent element:
```
button {
font-size: 1em;
padding: 0 1em;
border-radius: 0.5em;
background-color: #0f9432;
color: white;
}
```

