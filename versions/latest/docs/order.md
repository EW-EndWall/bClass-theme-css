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

# Tablet Order

- .tablet:order-first
- .hover:tablet:order-first
- .tablet:order-last
- .hover:tablet:order-last
- .tablet:order-0
- .hover:tablet:order-0
- .tablet:order-1,
- .hover:tablet:order-1
- .tablet:order-2
- .hover:tablet:order-2
- .tablet:order-3
- .hover:tablet:order-3
- .tablet:order-4
- .hover:tablet:order-4
- .tablet:order-5
- .hover:tablet:order-5
- .tablet:-order-1
- .hover:tablet:-order-1
- .tablet:-order-2
- .hover:tablet:-order-2
- .tablet:-order-3
- .hover:tablet:-order-3
- .tablet:-order-4
- .hover:tablet:-order-4
- .tablet:-order-5
- .hover:tablet:-order-5

```css
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  .tablet\:order-first,
  .hover\:tablet\:order-first:hover {
    order: -9999;
  }
  .tablet\:order-last,
  .hover\:tablet\:order-last:hover {
    order: 9999;
  }
  .tablet\:order-0,
  .hover\:tablet\:order-0:hover {
    order: 0;
  }
  .tablet\:order-1,
  .hover\:tablet\:order-1:hover {
    order: 1;
  }
  .tablet\:order-2,
  .hover\:tablet\:order-2:hover {
    order: 2;
  }
  .tablet\:order-3,
  .hover\:tablet\:order-3:hover {
    order: 3;
  }
  .tablet\:order-4,
  .hover\:tablet\:order-4:hover {
    order: 4;
  }
  .tablet\:order-5,
  .hover\:tablet\:order-5:hover {
    order: 5;
  }
  .tablet\:-order-1,
  .hover\:tablet\:-order-1:hover {
    order: -1;
  }
  .tablet\:-order-2,
  .hover\:tablet\:-order-2:hover {
    order: -2;
  }
  .tablet\:-order-3,
  .hover\:tablet\:-order-3:hover {
    order: -3;
  }
  .tablet\:-order-4,
  .hover\:tablet\:-order-4:hover {
    order: -4;
  }
  .tablet\:-order-5,
  .hover\:tablet\:-order-5:hover {
    order: -5;
  }
}
```

# Tablet Pc Order

- .tablet-pc:order-first
- .hover:tablet-pc:order-first
- .tablet-pc:order-last
- .hover:tablet-pc:order-last
- .tablet-pc:order-0
- .hover:tablet-pc:order-0
- .tablet-pc:order-1
- .hover:tablet-pc:order-1
- .tablet-pc:order-2
- .hover:tablet-pc:order-2
- .tablet-pc:order-3
- .hover:tablet-pc:order-3
- .tablet-pc:order-4
- .hover:tablet-pc:order-4
- .tablet-pc:order-5
- .hover:tablet-pc:order-5
- .tablet-pc:-order-1
- .hover:tablet-pc:-order-1
- .tablet-pc:-order-2
- .hover:tablet-pc:-order-2
- .tablet-pc:-order-3
- .hover:tablet-pc:-order-3
- .tablet-pc:-order-4
- .hover:tablet-pc:-order-4
- .tablet-pc:-order-5
- .hover:tablet-pc:-order-5

```css
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  .tablet-pc\:order-first,
  .hover\:tablet-pc\:order-first:hover {
    order: -9999;
  }
  .tablet-pc\:order-last,
  .hover\:tablet-pc\:order-last:hover {
    order: 9999;
  }
  .tablet-pc\:order-0,
  .hover\:tablet-pc\:order-0:hover {
    order: 0;
  }
  .tablet-pc\:order-1,
  .hover\:tablet-pc\:order-1:hover {
    order: 1;
  }
  .tablet-pc\:order-2,
  .hover\:tablet-pc\:order-2:hover {
    order: 2;
  }
  .tablet-pc\:order-3,
  .hover\:tablet-pc\:order-3:hover {
    order: 3;
  }
  .tablet-pc\:order-4,
  .hover\:tablet-pc\:order-4:hover {
    order: 4;
  }
  .tablet-pc\:order-5,
  .hover\:tablet-pc\:order-5:hover {
    order: 5;
  }
  .tablet-pc\:-order-1,
  .hover\:tablet-pc\:-order-1:hover {
    order: -1;
  }
  .tablet-pc\:-order-2,
  .hover\:tablet-pc\:-order-2:hover {
    order: -2;
  }
  .tablet-pc\:-order-3,
  .hover\:tablet-pc\:-order-3:hover {
    order: -3;
  }
  .tablet-pc\:-order-4,
  .hover\:tablet-pc\:-order-4:hover {
    order: -4;
  }
  .tablet-pc\:-order-5,
  .hover\:tablet-pc\:-order-5:hover {
    order: -5;
  }
}
```

# Pc Order

- .pc:order-first
- .hover:pc:order-first
- .pc:order-last
- .hover:pc:order-last
- .pc:order-0
- .hover:pc:order-0
- .pc:order-1
- .hover:pc:order-1
- .pc:order-2
- .hover:pc:order-2
- .pc:order-3
- .hover:pc:order-3
- .pc:order-4
- .hover:pc:order-4
- .pc:order-5
- .hover:pc:order-5
- .pc:-order-1
- .hover:pc:-order-1
- .pc:-order-2
- .hover:pc:-order-2
- .pc:-order-3
- .hover:pc:-order-3
- .pc:-order-4
- .hover:pc:-order-4
- .pc:-order-5
- .hover:pc:-order-5

```css
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .pc\:order-first,
  .hover\:pc\:order-first:hover {
    order: -9999;
  }
  .pc\:order-last,
  .hover\:pc\:order-last:hover {
    order: 9999;
  }
  .pc\:order-0,
  .hover\:pc\:order-0:hover {
    order: 0;
  }
  .pc\:order-1,
  .hover\:pc\:order-1:hover {
    order: 1;
  }
  .pc\:order-2,
  .hover\:pc\:order-2:hover {
    order: 2;
  }
  .pc\:order-3,
  .hover\:pc\:order-3:hover {
    order: 3;
  }
  .pc\:order-4,
  .hover\:pc\:order-4:hover {
    order: 4;
  }
  .pc\:order-5,
  .hover\:pc\:order-5:hover {
    order: 5;
  }
  .pc\:-order-1,
  .hover\:pc\:-order-1:hover {
    order: -1;
  }
  .pc\:-order-2,
  .hover\:pc\:-order-2:hover {
    order: -2;
  }
  .pc\:-order-3,
  .hover\:pc\:-order-3:hover {
    order: -3;
  }
  .pc\:-order-4,
  .hover\:pc\:-order-4:hover {
    order: -4;
  }
  .pc\:-order-5,
  .hover\:pc\:-order-5:hover {
    order: -5;
  }
}
```

# Tv

- .tv:order-first
- .hover:tv:order-first
- .tv:order-last
- .hover:tv:order-last
- .tv:order-0
- .hover:tv:order-0
- .tv:order-1
- .hover:tv:order-1
- .tv:order-2
- .hover:tv:order-2
- .tv:order-3
- .hover:tv:order-3
- .tv:order-4
- .hover:tv:order-4
- .tv:order-5
- .hover:tv:order-5
- .tv:-order-1
- .hover:tv:-order-1
- .tv:-order-2
- .hover:tv:-order-2
- .tv:-order-3
- .hover:tv:-order-3
- .tv:-order-4
- .hover:tv:-order-4
- .tv:-order-5
- .hover:tv:-order-5

```css
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  .tv\:order-first,
  .hover\:tv\:order-first:hover {
    order: -9999;
  }
  .tv\:order-last,
  .hover\:tv\:order-last:hover {
    order: 9999;
  }
  .tv\:order-0,
  .hover\:tv\:order-0:hover {
    order: 0;
  }
  .tv\:order-1,
  .hover\:tv\:order-1:hover {
    order: 1;
  }
  .tv\:order-2,
  .hover\:tv\:order-2:hover {
    order: 2;
  }
  .tv\:order-3,
  .hover\:tv\:order-3:hover {
    order: 3;
  }
  .tv\:order-4,
  .hover\:tv\:order-4:hover {
    order: 4;
  }
  .tv\:order-5,
  .hover\:tv\:order-5:hover {
    order: 5;
  }
  .tv\:-order-1,
  .hover\:tv\:-order-1:hover {
    order: -1;
  }
  .tv\:-order-2,
  .hover\:tv\:-order-2:hover {
    order: -2;
  }
  .tv\:-order-3,
  .hover\:tv\:-order-3:hover {
    order: -3;
  }
  .tv\:-order-4,
  .hover\:tv\:-order-4:hover {
    order: -4;
  }
  .tv\:-order-5,
  .hover\:tv\:-order-5:hover {
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
