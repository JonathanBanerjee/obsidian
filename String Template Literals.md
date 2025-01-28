
Without Template literals.

```
let product = 'Artichoke';

let price = 3.99

price = 2.25
>2.25

let qty = 5;

You bought x artichokes, price = 5 * price

"You bought" + qty + " " + product + ". Total is: " + price * qty 
> You bought 5 artichoke, Total is: 11.25"
```



With template literals.
Template literals are strings that allow embedded expressions, which will be evaluated and then turned into a resulting string.

E.g. 
```
'I counted ${3 + 4} sheep`;
// "I counted 7 sheep"
```

Note: You HAVE to use the BACKTICK, not single or double quotes.
Whatever is put in the curly braces will be treated as an expression and will be evaluated as JavaScript. 

```
`You bought ${qty} ${product.toUppercCase()}. Total is: $${price * qty}`

// "You bought 5 ARTICHOKES. Total is: $11.25"
```

Note: You have used a double dollar sign to escape the string, and add a dollar sign to the price. 
Also, you can add methods to the JavaScript. In the instance above, I have made the project uppercase. 