Bootstrap is actually built on top of flexbox.

So for example, you can include flexbox utilities in bootstrap:

```
<div class="row align-items-end">
```

You can also change the behaviour of the flex-box depending on the screensize by using the following for example (Look at the use of md for medium):
```
<div class="col-md-4 bg-info">
```


The following will allow the content to move to the start (to the left) of the page when it is a large screen:
```
<div class="row border justify-content-center justify-content-lg-start">
```