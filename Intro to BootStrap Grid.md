Allows us to create responsive layout where the division of space might change depending on the screen size. 

The grid system only works inside of a container. 

Every row in bootstrap has 12 units of space to divide up. E.g. if it's 50% and 50% each box is 6 units. 

```
<div class="container">

<h1 class="display-1 text-center text-primary">The grid system</h1>

<div class="row">

<div class="col-2 bg-success">I am 2 units</div>

<div class="col-8 bg-danger">I am 8 units</div>

<div class="col-2 bg-success">I am 2 units</div>

</div>

  

<div class="row">

<div class="col-3 bg-success">I am 3 units</div>

<div class="col-6 bg-danger">I am 6 units</div>

<div class="col-3 bg-success">I am 3 units</div>

</div>

  // Auto sizing the columns can be done by not adding a number to the col class.

<div class="row">

<div class="col bg-primary">I am auto sized</div>

<div class="col bg-secondary">I am auto sized</div>

<div class="col-9 bg-primary">I am auto sized</div>

<div class="col bg-secondary">I am auto sized</div>

</div>

</div>
```