# Order

The order CSS property sets the order to lay out an item in a flex or grid container. Items in a container are sorted by ascending order value and then by their source code order. Items not given an explicit order value are assigned the default value of 0.

- .order-first
- .hover:order-first
- .order-last
- .hover:order-last
- .order-0
- .hover:order-0
- .order-1,
- .hover:order-1
- .order-2
- .hover:order-2
- .order-3
- .hover:order-3
- .order-4
- .hover:order-4
- .order-5
- .hover:order-5
- .-order-1
- .hover:-order-1
- .-order-2
- .hover:-order-2
- .-order-3
- .hover:-order-3
- .-order-4
- .hover:-order-4
- .-order-5
- .hover:-order-5

```css
.order-first,
.hover\:order-first:hover {
  order: -9999;
}
.order-last,
.hover\:order-last:hover {
  order: 9999;
}
.order-0,
.hover\:order-0:hover {
  order: 0;
}
.order-1,
.hover\:order-1:hover {
  order: 1;
}
.order-2,
.hover\:order-2:hover {
  order: 2;
}
.order-3,
.hover\:order-3:hover {
  order: 3;
}
.order-4,
.hover\:order-4:hover {
  order: 4;
}
.order-5,
.hover\:order-5:hover {
  order: 5;
}
.-order-1,
.hover\:-order-1:hover {
  order: -1;
}
.-order-2,
.hover\:-order-2:hover {
  order: -2;
}
.-order-3,
.hover\:-order-3:hover {
  order: -3;
}
.-order-4,
.hover\:-order-4:hover {
  order: -4;
}
.-order-5,
.hover\:-order-5:hover {
  order: -5;
}
```

### example

```html
<div class="container">
  <p>Hello World ! 1</p>
  <p class="-order-1">Hello World ! 2</p>
</div>
```
