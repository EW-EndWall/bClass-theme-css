# Float

The float CSS property places an element on the left or right side of its container, allowing text and inline elements to wrap around it. The element is removed from the normal flow of the page, though still remaining a part of the flow (in contrast to absolute positioning).

- .float-start
- .hover:float-start
- .float-end
- .hover:float-end
- .float-left
- .hover:float-left
- .float-right
- .hover:float-right
- .float-none
- .hover:float-none

```css
.float-start,
.hover\:float-start:hover {
  float: inline-start;
}
.float-end,
.hover\:float-end:hover {
  float: inline-end;
}
.float-left,
.hover\:float-left:hover {
  float: left;
}
.float-right,
.hover\:float-right:hover {
  float: right;
}
.float-none,
.hover\:float-none:hover {
  float: none;
}
```

### example

```html
<div class="container">
  <p class="float-right">Hello World !</p>
</div>
```
