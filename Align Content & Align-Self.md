Aligns content along the cross axis but only when we have multiple rows or columns depending which layout we are in. Align-Content controls the space between either the rows or columns, depending where the cross-axis is.

**Note:** This property only takes effect on multi-line flexible containers, where `flex-wrap` is set to either `wrap` or `wrap-reverse`). A single-line flexible container (i.e. where `flex-wrap` is set to its default value, `no-wrap`) will not reflect `align-content`.
#### Flex Start
`align-content: flex-start;`

We still have our rows but the content moves to the left in this case:
![[Screenshot 2024-04-25 at 12.10.11.png]]


![[Screenshot 2024-04-25 at 12.08.39.png]]


#### Flex End
`align-content: flex-end;`

We still have our rows but the content moves to the right in this case:
![[Screenshot 2024-04-25 at 12.11.46.png]]

![[Screenshot 2024-04-25 at 12.12.13.png]]



Align-self is very similar to align-items but it applies to a single element. 

```
div:nth-last-of-type(3) {
align-self: flex-end;
}
```
