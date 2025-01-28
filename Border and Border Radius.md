The main border properties:

border-width - Controls the thickness of the border.

bordor-color - Controls the colour of the border.

border-style - controls the style of the border (dashed, solid etc). 

For border width, pixels are common to use.  In order to see the border, you will need to add a border-color as well as a border-style. 

If you turn on:
```
box-sizing: border-box;
```
This will make sure that the outside edge of the border is kept within the entire element. (This helps a lot for sizing!)
E.g. when you set an element to be 200px wide, it will be exactly 200px wide. 

You can provide the border width, style and colour in one go: Width | Style | Colour

```
border: 1rem dashed #32a1c3; 
```

You can still change individual sides after, e.g:
```
border-left-style: dotted;
```


border-radius allows us to set the radius of the corners (for more rounded edges), this is typically set using a percentage. 