
For a rounded border and a shadowed button:

```
<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8" />

<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<link

href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"

rel="stylesheet"

integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"

crossorigin="anonymous"

/>

<script

src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"

integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"

crossorigin="anonymous"

></script>

<link rel="stylesheet" href="other-utilities.css" />

</head>

<body>

<div class="container">

<h1 class="display-1">Utilities</h1>

<div class="row">

<div class="col-md-4 border rounded border-success">

<button class="btn btn-info shadow-sm">Shadow</button>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Incidunt, in

neque nihil perspiciatis laborum ad mollitia modi architecto velit

fugit quod nisi sapiente ipsam, id eveniet quia adipisci corrupti et!

</div>

</div>

</div>

</body>

</html>
```


##### Margin and Padding
##### Notation 

Spacing utilities that apply to all breakpoints, from `xs` to `xxl`, have no breakpoint abbreviation in them. This is because those classes are applied from `min-width: 0` and up, and thus are not bound by a media query. The remaining breakpoints, however, do include a breakpoint abbreviation.

The classes are named using the format `{property}{sides}-{size}` for `xs` and `{property}{sides}-{breakpoint}-{size}` for `sm`, `md`, `lg`, `xl`, and `xxl`.

Where _property_ is one of:

- `m` - for classes that set `margin`
- `p` - for classes that set `padding`

Where _sides_ is one of:

- `t` - for classes that set `margin-top` or `padding-top`
- `b` - for classes that set `margin-bottom` or `padding-bottom`
- `s` - (start) for classes that set `margin-left` or `padding-left` in LTR, `margin-right` or `padding-right` in RTL
- `e` - (end) for classes that set `margin-right` or `padding-right` in LTR, `margin-left` or `padding-left` in RTL
- `x` - for classes that set both `*-left` and `*-right`
- `y` - for classes that set both `*-top` and `*-bottom`
- blank - for classes that set a `margin` or `padding` on all 4 sides of the element

Where _size_ is one of:

- `0` - for classes that eliminate the `margin` or `padding` by setting it to `0`
- `1` - (by default) for classes that set the `margin` or `padding` to `$spacer * .25`
- `2` - (by default) for classes that set the `margin` or `padding` to `$spacer * .5`
- `3` - (by default) for classes that set the `margin` or `padding` to `$spacer`
- `4` - (by default) for classes that set the `margin` or `padding` to `$spacer * 1.5`
- `5` - (by default) for classes that set the `margin` or `padding` to `$spacer * 3`
- `auto` - for classes that set the `margin` to auto

(You can add more sizes by adding entries to the `$spacers` Sass map variable.)


e.g.

```
<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8" />

<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<link

href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"

rel="stylesheet"

integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"

crossorigin="anonymous"

/>

<script

src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"

integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"

crossorigin="anonymous"

></script>

<link rel="stylesheet" href="other-utilities.css" />

</head>

<body>

<div class="container">

<h1 class="display-1 mb-5">Utilities</h1>

<div class="row">

<div class="col-md-4 border rounded border-success">

<button class="btn btn-info shadow-sm">Shadow</button>

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Incidunt, in

neque nihil perspiciatis laborum ad mollitia modi architecto velit

fugit quod nisi sapiente ipsam, id eveniet quia adipisci corrupti et!

</div>

</div>

  

<div class>

<button class="btn btn-primary p-0">Padding 0</button

><button class="btn btn-primary p-1">Padding 1</button

><button class="btn btn-primary p-2">Padding 2</button

><button class="btn btn-primary p-3">Padding 3</button

><button class="btn btn-primary p-4">Padding 4</button

><button class="btn btn-primary p-5">Padding 5</button>

</div>

  

<div class="mt-5">

<button class="btn btn-primary p-0 pt-5">Padding Top</button

><button class="btn btn-primary p-1 pl-5">Padding Left</button

><button class="btn btn-primary p-2 pb-5">Padding Bottom</button

><button class="btn btn-primary p-3 pr-5">Padding Right</button

><button class="btn btn-primary p-4 px-5">Padding X</button

><button class="btn btn-primary p-5 px-5">Padding Y</button>

</div>

  

<button class="btn btn-danger p-0 p p-sm-1 p-md-2 p-lg-3 pg-xl-5">

I change!

</button>

</div>

</body>

</html>
```