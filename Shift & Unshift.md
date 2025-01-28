shift - Remove from start
unshift - Add to start.

Using Shift:

```
movieLine
> ["tom", "nancy", "oliver", "eva", "harry"]

movieLine.shift()
> "Tom"

movieLine 
> ["nancy", "oliver", "eva", "harry"]

// using a variable:
nextPatron = movieLine.shift()
nextPatron
> "nancy"

movieLine
> ["oliver", "eva", "harry"]

```


Using unshift:
```
movieLine.push('jerry', 'deniz', 'kevin', 'carly')
> 4
 movieLine 
> ["jerry", "deniz", "kevin", "carly"] 
movieLine.unshift('vip');
movieLine
> ["vip", "jerry", "deniz", "kevin", "carly"] 
```
