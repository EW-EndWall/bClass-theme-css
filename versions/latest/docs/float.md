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

# Mobile Float

- .mobile:float-start
- .hover:mobile:float-start
- .mobile:float-end
- .hover:mobile:float-end
- .mobile:float-left
- .hover:mobile:float-left
- .mobile:float-right
- .hover:mobile:float-right
- .mobile:float-none
- .hover:mobile:float-none

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:float-start,
  .hover\:mobile\:float-start:hover {
    float: inline-start;
  }
  .mobile\:float-end,
  .hover\:mobile\:float-end:hover {
    float: inline-end;
  }
  .mobile\:float-left,
  .hover\:mobile\:float-left:hover {
    float: left;
  }
  .mobile\:float-right,
  .hover\:mobile\:float-right:hover {
    float: right;
  }
  .mobile\:float-none,
  .hover\:mobile\:float-none:hover {
    float: none;
  }
}
```

# Tablet Float

- .tablet:float-start
- .hover:tablet:float-start
- .tablet:float-end
- .hover:tablet:float-end
- .tablet:float-left
- .hover:tablet:float-left
- .tablet:float-right
- .hover:tablet:float-right
- .tablet:float-none
- .hover:tablet:float-none

```css
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  .tablet\:float-start,
  .hover\:tablet\:float-start:hover {
    float: inline-start;
  }
  .tablet\:float-end,
  .hover\:tablet\:float-end:hover {
    float: inline-end;
  }
  .tablet\:float-left,
  .hover\:tablet\:float-left:hover {
    float: left;
  }
  .tablet\:float-right,
  .hover\:tablet\:float-right:hover {
    float: right;
  }
  .tablet\:float-none,
  .hover\:tablet\:float-none:hover {
    float: none;
  }
}
```

# Tablet Pc Float

- .tablet-pc:float-start
- .hover:tablet-pc:float-start
- .tablet-pc:float-end
- .hover:tablet-pc:float-end
- .tablet-pc:float-left
- .hover:tablet-pc:float-left
- .tablet-pc:float-right
- .hover:tablet-pc:float-right
- .tablet-pc:float-none
- .hover:tablet-pc:float-none

```css
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  .tablet-pc\:float-start,
  .hover\:tablet-pc\:float-start:hover {
    float: inline-start;
  }
  .tablet-pc\:float-end,
  .hover\:tablet-pc\:float-end:hover {
    float: inline-end;
  }
  .tablet-pc\:float-left,
  .hover\:tablet-pc\:float-left:hover {
    float: left;
  }
  .tablet-pc\:float-right,
  .hover\:tablet-pc\:float-right:hover {
    float: right;
  }
  .tablet-pc\:float-none,
  .hover\:tablet-pc\:float-none:hover {
    float: none;
  }
}
```

# Pc Float

- .pc:float-start
- .hover:pc:float-start
- .pc:float-end
- .hover:pc:float-end
- .pc:float-left
- .hover:pc:float-left
- .pc:float-right
- .hover:pc:float-right
- .pc:float-none
- .hover:pc:float-none

```css
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .pc\:float-start,
  .hover\:pc\:float-start:hover {
    float: inline-start;
  }
  .pc\:float-end,
  .hover\:pc\:float-end:hover {
    float: inline-end;
  }
  .pc\:float-left,
  .hover\:pc\:float-left:hover {
    float: left;
  }
  .pc\:float-right,
  .hover\:pc\:float-right:hover {
    float: right;
  }
  .pc\:float-none,
  .hover\:pc\:float-none:hover {
    float: none;
  }
}
```

# Tv Float

- .tv:float-start
- .hover:tv:float-start
- .tv:float-end
- .hover:tv:float-end
- .tv:float-left
- .hover:tv:float-left
- .tv:float-right
- .hover:tv:float-right
- .tv:float-none
- .hover:tv:float-none

```css
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  .tv\:float-start,
  .hover\:tv\:float-start:hover {
    float: inline-start;
  }
  .tv\:float-end,
  .hover\:tv\:float-end:hover {
    float: inline-end;
  }
  .tv\:float-left,
  .hover\:tv\:float-left:hover {
    float: left;
  }
  .tv\:float-right,
  .hover\:tv\:float-right:hover {
    float: right;
  }
  .tv\:float-none,
  .hover\:tv\:float-none:hover {
    float: none;
  }
}
```

### example

```html
<div class="container">
  <p class="float-right">Hello World !</p>
</div>
```
