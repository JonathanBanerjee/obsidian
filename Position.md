Sets how an element is positioned in a document. This also determines how Top, Right, Bottom and Left work. 


#### Static
If you set the position to static, this is the default. What the current element is set as. So it will have no affect on the way the element is positioned if it is positioned statically. 

#### Relative
The element is positioned according to the normal flow of the document and then offsets it relative to itself based on the values top, right, left and bottom. It is placed relative to where it normally would be. 

This would shift the middle square down by 100px:
```
#relative #middle {
position: relative;
top: 100px;
}
```
You can use negative values, e.g. -100px would make it go up rather than down. 

#### Absolute
This is where the element is removed from the normal document flow, and no space is created for the element in the page layout. It is positioned relative to its closest positioned ancestor, if any; otherwise, it is placed relative to the initial containing block (in most cases this is the body). 

This on it's own will behave differently and go to the near top of the page:

```
#absolute #middle {
position: absolute;
top: 50px;
left: 50px;
}
```

However, if you include this as it's the parent, it will move to the bottom:
```
#absolute {
position: relative;
}
```

#### Fixed
This is similar to absolute but it is relative to the initial containing block and has nothing to do with the parental elements. 

```
#fixed #middle {
position: fixed;
top: 0px;
left: 400px;
}
```
This can be used as a navbar that stays at the top of the page at all times for example. 

#### Sticky
This is the same as fixed, but it starts as not-fixed until it hits the edge of the screen and it sticks to the top of the screen when a user starts scrolling. 