
```
section {
width: 80%;
height: 800px;
background-image: url(https://images.unsplash.com/photo-1519681393784-d120267933ba?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D);
margin: 0 auto;
background-size: contain;
}
```


background-size decides how the image is sized.

E.g. 
```
background-size: contain;
```
scales the image as large as possible without cropping or stretching the image.


```
background-size: cover;
```
Scales the image as large as possible without stretching the image. If the proportions of the image differ from the element, it is cropped vertically or horizontally so that no empty space remains.

These can be all combined together in the shorthand version in any way possible. 

Note that bg-size value may only be included immediately after the <position> , separated with the '/' character, like this: "center/80%" 

e.g:
 section {
width: 80%;
height: 800px;
background-size: cover;
background-image: bottom; */
background: no-repeat center/40%
url(https://images.unsplash.com/photo-1519681393784-d120267933ba?q=80&w=2940&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D),
burlywood;
margin: 0 auto;
} 



