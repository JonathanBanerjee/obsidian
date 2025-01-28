Specificity is how the browser decides which rules to apply when multiple rules could apply to the same element.


It is a measure of how specific a given selector is. The more specific selector "wins".

Below, the selectors in the .post block are more specific, and so would override the other selector.

```
.post button:hover {

background-color: #e63946;

color: #f1faee;

}

  

button:hover {

background-color: olive;

font-size: 10px;

}
```


Order of specificity:
ID > Class > Element. 
![[Screenshot 2024-04-21 at 12.33.40.png]]
In this case, ID is the most specific. 

You can check the specificity here:
https://specificity.keegan.st 

Even if you have 28 elements selected, 1 class would still be more powerful. 