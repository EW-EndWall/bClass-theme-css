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

# Mobile Order

- .mobile:order-first
- .hover:mobile:order-first
- .mobile:order-last
- .hover:mobile:order-last
- .mobile:order-0
- .hover:mobile:order-0
- .mobile:order-1
- .hover:mobile:order-1
- .mobile:order-2
- .hover:mobile:order-2
- .mobile:order-3
- .hover:mobile:order-3
- .mobile:order-4
- .hover:mobile:order-4
- .mobile:order-5
- .hover:mobile:order-5
- .mobile:-order-1
- .hover:mobile:-order-1
- .mobile:-order-2
- .hover:mobile:-order-2
- .mobile:-order-3
- .hover:mobile:-order-3
- .mobile:-order-4
- .hover:mobile:-order-4
- .mobile:-order-5
- .hover:mobile:-order-5

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:order-first,
  .hover\:mobile\:order-first:hover {
    order: -9999;
  }
  .mobile\:order-last,
  .hover\:mobile\:order-last:hover {
    order: 9999;
  }
  .mobile\:order-0,
  .hover\:mobile\:order-0:hover {
    order: 0;
  }
  .mobile\:order-1,
  .hover\:mobile\:order-1:hover {
    order: 1;
  }
  .mobile\:order-2,
  .hover\:mobile\:order-2:hover {
    order: 2;
  }
  .mobile\:order-3,
  .hover\:mobile\:order-3:hover {
    order: 3;
  }
  .mobile\:order-4,
  .hover\:mobile\:order-4:hover {
    order: 4;
  }
  .mobile\:order-5,
  .hover\:mobile\:order-5:hover {
    order: 5;
  }
  .mobile\:-order-1,
  .hover\:mobile\:-order-1:hover {
    order: -1;
  }
  .mobile\:-order-2,
  .hover\:mobile\:-order-2:hover {
    order: -2;
  }
  .mobile\:-order-3,
  .hover\:mobile\:-order-3:hover {
    order: -3;
  }
  .mobile\:-order-4,
  .hover\:mobile\:-order-4:hover {
    order: -4;
  }
  .mobile\:-order-5,
  .hover\:mobile\:-order-5:hover {
    order: -5;
  }
}
```

### example

```html
<div class="container">
  <p>Hello World ! 1</p>
  <p class="-order-1">Hello World ! 2</p>
</div>
```
