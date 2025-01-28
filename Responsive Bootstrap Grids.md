
This feature enables you to build a responsive layout making use of the built-in breakpoints in bootstrap.

How this works:
```
<div class="col-xl-4 col-md-6">
```

From medium and above, I want 6 units, from extra-large and above I want 4 units.

![[Screenshot 2024-05-28 at 09.35.43.png]]


Images:
```
<div class="row">

<div class="col-xl-4 col-md-6">

<img

class="img-fluid"

src="https://images.unsplash.com/photo-1518791841217-8f162f1e1131"

alt="Shallow focus photo of an orange cat"

/>

</div>

<div class="col-xl-4 col-md-6">

<img

class="img-fluid"

src="https://images.unsplash.com/photo-1583795128727-6ec3642408f8?q=80&w=3157&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"

alt="Another Cat"

/>

</div>

<div class="col-xl-4 col-md-6">

<img

class="img-fluid"

src=" https://images.unsplash.com/photo-1541781774459-bb2af2f05b55?q=80&w=2960&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"

alt="Sleepy Cat"

/>

</div>

</div>
```


This is what it looks like:

![[Screenshot 2024-05-28 at 10.24.38.png]]


Smaller screen view:
![[Screenshot 2024-05-28 at 10.24.57.png]]


To remove the spacing (removing the gutters) you need to set the row to 0:

```
<div class="row g-0">
```