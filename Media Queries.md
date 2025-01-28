These allow us to modify our styles depending on particular parameters like screen width or device type. 

All media queries begin with @media. 

e.g. (Note this will only do it for EXACTLY 360 pixels)
```
@media (width: 360px) {
div {
color: red;
}
}
```


To avoid this, you can use min-width and max width. Note this is the width of the viewport. 

You can combine media queries like this:
```
@media (min-width: 600px) and (max-width: 800px) {
h1 {
color: purple;
}
}
```

