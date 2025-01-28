
[[Rotate]]
[[Scale]]
[[Translate]]
[[Skew]]

Note: you can stack all of them:
```
section:nth-of-type(2) h1:nth-of-type(4) {
transform: translateX(-500px) rotate(0.5turn) scaleY(1.5);
}
```

Everything we do will apply to not only the parent element but also it's contents:

```
section:nth-of-type(2) {
transform: scale(0.7) translateX(500px);
}
```
This will make the elements scale to 0.7 in size and move 500px to the left.