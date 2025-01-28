Similar to RGB(0, 0, 0), there is RGBA(0, 0, 0, 0)

The A stands for alpha and describes the transparency of the colour. 

It is a value from 0 to 1, not 0 to 255.

Example:
```
#rgba {
width: 50%;
height: 50%;
background-color: rgba(255, 255, 255, 0.7);
}
```

Opacity on the otherhand will affect the entire div:

```
#opacity {
width: 50%;
height: 50%;
background-color: yellow;
opacity: 0.3;
}
```
This will affect the button inside the div. 

The alpha channel can also be written in hexadecimal:

It has the same properties as regular hexadecimal:
#00cca0 but then the last two digits will go from 00 to FF
e.g. #00cca0FF 

Note it is easier to use RGBA colours than hex.