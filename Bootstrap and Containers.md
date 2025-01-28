
When you add Bootstrap to a document, be sure to include the link before your link to css in the HTML, that way your own styles will not be overwritten by bootstrap.

The scripts should be put below the closing body tags.

The following will make the container behave differently.

```
<div class="container-fluid">
  <!-- Content here -->
</div>
```
<div class="container-fluid">
  <!-- Content here -->
</div>
<div class="container">
  <!-- Content here -->
</div>

```
<div class="container">
  <!-- Content here -->
</div>
```