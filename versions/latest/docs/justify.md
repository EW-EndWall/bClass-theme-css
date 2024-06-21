# Justify Content

The CSS justify-content property defines how the browser distributes space between and around content items along the main-axis of a flex container, and the inline axis of a grid container.

- .justify-content-start
- .hover:justify-content-start
- .justify-content-end
- .hover:justify-content-end
- .justify-content-center
- .hover:justify-content-center
- .justify-content-between
- .hover:justify-content-between
- .justify-content-around
- .hover:justify-content-around
- .justify-content-evenly
- .hover:justify-content-evenly
- .justify-content-stretch
- .hover:justify-content-stretch

```css
.justify-content-start,
.hover\:justify-content-start:hover {
  justify-content: flex-start;
}
.justify-content-end,
.hover\:justify-content-end:hover {
  justify-content: flex-end;
}
.justify-content-center,
.hover\:justify-content-center:hover {
  justify-content: center;
}
.justify-content-between,
.hover\:justify-content-between:hover {
  justify-content: space-between;
}
.justify-content-around,
.hover\:justify-content-around:hover {
  justify-content: space-around;
}
.justify-content-evenly,
.hover\:justify-content-evenly:hover {
  justify-content: space-evenly;
}
.justify-content-stretch,
.hover\:justify-content-stretch:hover {
  justify-content: stretch;
}
```

# Mobile Justify Content

- .mobile:justify-content-start
- .hover:mobile:justify-content-start
- .mobile:justify-content-end
- .hover:mobile:justify-content-end
- .mobile:justify-content-center
- .hover:mobile:justify-content-center
- .mobile:justify-content-between
- .hover:mobile:justify-content-between
- .mobile:justify-content-around
- .hover:mobile:justify-content-around

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:justify-content-start,
  .hover\:mobile\:justify-content-start:hover {
    justify-content: flex-start;
  }
  .mobile\:justify-content-end,
  .hover\:mobile\:justify-content-end:hover {
    justify-content: flex-end;
  }
  .mobile\:justify-content-center,
  .hover\:mobile\:justify-content-center:hover {
    justify-content: center;
  }
  .mobile\:justify-content-between,
  .hover\:mobile\:justify-content-between:hover {
    justify-content: space-between;
  }
  .mobile\:justify-content-around,
  .hover\:mobile\:justify-content-around:hover {
    justify-content: space-around;
  }
}
```

# Tablet Justify Content

- .tablet:justify-content-start
- .hover:tablet:justify-content-start
- .tablet:justify-content-end
- .hover:tablet:justify-content-end
- .tablet:justify-content-center
- .hover:tablet:justify-content-center
- .tablet:justify-content-between
- .hover:tablet:justify-content-between
- .tablet:justify-content-around
- .hover:tablet:justify-content-around

```css
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  .tablet\:justify-content-start,
  .hover\:tablet\:justify-content-start:hover {
    justify-content: flex-start;
  }
  .tablet\:justify-content-end,
  .hover\:tablet\:justify-content-end:hover {
    justify-content: flex-end;
  }
  .tablet\:justify-content-center,
  .hover\:tablet\:justify-content-center:hover {
    justify-content: center;
  }
  .tablet\:justify-content-between,
  .hover\:tablet\:justify-content-between:hover {
    justify-content: space-between;
  }
  .tablet\:justify-content-around,
  .hover\:tablet\:justify-content-around:hover {
    justify-content: space-around;
  }
}
```

# Tablet Pc Justify Content

- .tablet-pc:justify-content-start
- .hover:tablet-pc:justify-content-start
- .tablet-pc:justify-content-end
- .hover:tablet-pc:justify-content-end
- .tablet-pc:justify-content-center
- .hover:tablet-pc:justify-content-center
- .tablet-pc:justify-content-between
- .hover:tablet-pc:justify-content-between
- .tablet-pc:justify-content-around
- .hover:tablet-pc:justify-content-around

```css
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  .tablet-pc\:justify-content-start,
  .hover\:tablet-pc\:justify-content-start:hover {
    justify-content: flex-start;
  }
  .tablet-pc\:justify-content-end,
  .hover\:tablet-pc\:justify-content-end:hover {
    justify-content: flex-end;
  }
  .tablet-pc\:justify-content-center,
  .hover\:tablet-pc\:justify-content-center:hover {
    justify-content: center;
  }
  .tablet-pc\:justify-content-between,
  .hover\:tablet-pc\:justify-content-between:hover {
    justify-content: space-between;
  }
  .tablet-pc\:justify-content-around,
  .hover\:tablet-pc\:justify-content-around:hover {
    justify-content: space-around;
  }
}
```

# Pc Justify Content

- .pc:justify-content-start
- .hover:pc:justify-content-start
- .pc:justify-content-end
- .hover:pc:justify-content-end
- .pc:justify-content-center
- .hover:pc:justify-content-center
- .pc:justify-content-between
- .hover:pc:justify-content-between
- .pc:justify-content-around
- .hover:pc:justify-content-around

```css
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .pc\:justify-content-start,
  .hover\:pc\:justify-content-start:hover {
    justify-content: flex-start;
  }
  .pc\:justify-content-end,
  .hover\:pc\:justify-content-end:hover {
    justify-content: flex-end;
  }
  .pc\:justify-content-center,
  .hover\:pc\:justify-content-center:hover {
    justify-content: center;
  }
  .pc\:justify-content-between,
  .hover\:pc\:justify-content-between:hover {
    justify-content: space-between;
  }
  .pc\:justify-content-around,
  .hover\:pc\:justify-content-around:hover {
    justify-content: space-around;
  }
}
```

# Tv Justify Content

- .tv:justify-content-start
- .hover:tv:justify-content-start
- .tv:justify-content-end
- .hover:tv:justify-content-end
- .tv:justify-content-center
- .hover:tv:justify-content-center
- .tv:justify-content-between
- .hover:tv:justify-content-between
- .tv:justify-content-around
- .hover:tv:justify-content-around

```css
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  .tv\:justify-content-start,
  .hover\:tv\:justify-content-start:hover {
    justify-content: flex-start;
  }
  .tv\:justify-content-end,
  .hover\:tv\:justify-content-end:hover {
    justify-content: flex-end;
  }
  .tv\:justify-content-center,
  .hover\:tv\:justify-content-center:hover {
    justify-content: center;
  }
  .tv\:justify-content-between,
  .hover\:tv\:justify-content-between:hover {
    justify-content: space-between;
  }
  .tv\:justify-content-around,
  .hover\:tv\:justify-content-around:hover {
    justify-content: space-around;
  }
}
```

# Tablet Max Justify Content

- .tablet-max:justify-content-start
- .hover:tablet-max:justify-content-start
- .tablet-max:justify-content-end
- .hover:tablet-max:justify-content-end
- .tablet-max:justify-content-center
- .hover:tablet-max:justify-content-center
- .tablet-max:justify-content-between
- .hover:tablet-max:justify-content-between
- .tablet-max:justify-content-around
- .hover:tablet-max:justify-content-around

```css
/* tablet < 768px */
@media screen and (max-width: 768px) {
  .tablet-max\:justify-content-start,
  .hover\:tablet-max\:justify-content-start:hover {
    justify-content: flex-start;
  }
  .tablet-max\:justify-content-end,
  .hover\:tablet-max\:justify-content-end:hover {
    justify-content: flex-end;
  }
  .tablet-max\:justify-content-center,
  .hover\:tablet-max\:justify-content-center:hover {
    justify-content: center;
  }
  .tablet-max\:justify-content-between,
  .hover\:tablet-max\:justify-content-between:hover {
    justify-content: space-between;
  }
  .tablet-max\:justify-content-around,
  .hover\:tablet-max\:justify-content-around:hover {
    justify-content: space-around;
  }
}
```

# Tablet Pc Max Justify Content

- .tablet-pc-max:justify-content-start
- .hover:tablet-pc-max:justify-content-start
- .tablet-pc-max:justify-content-end
- .hover:tablet-pc-max:justify-content-end
- .tablet-pc-max:justify-content-center
- .hover:tablet-pc-max:justify-content-center
- .tablet-pc-max:justify-content-between
- .hover:tablet-pc-max:justify-content-between
- .tablet-pc-max:justify-content-around
- .hover:tablet-pc-max:justify-content-around

```css
/* tablet-pc < 992 */
@media screen and (max-width: 992px) {
  .tablet-pc-max\:justify-content-start,
  .hover\:tablet-pc-max\:justify-content-start:hover {
    justify-content: flex-start;
  }
  .tablet-pc-max\:justify-content-end,
  .hover\:tablet-pc-max\:justify-content-end:hover {
    justify-content: flex-end;
  }
  .tablet-pc-max\:justify-content-center,
  .hover\:tablet-pc-max\:justify-content-center:hover {
    justify-content: center;
  }
  .tablet-pc-max\:justify-content-between,
  .hover\:tablet-pc-max\:justify-content-between:hover {
    justify-content: space-between;
  }
  .tablet-pc-max\:justify-content-around,
  .hover\:tablet-pc-max\:justify-content-around:hover {
    justify-content: space-around;
  }
}
```

# Pc Max Justify Content

- .pc-max:justify-content-start
- .hover:pc-max:justify-content-start
- .pc-max:justify-content-end
- .hover:pc-max:justify-content-end
- .pc-max:justify-content-center
- .hover:pc-max:justify-content-center
- .pc-max:justify-content-between
- .hover:pc-max:justify-content-between
- .pc-max:justify-content-around
- .hover:pc-max:justify-content-around

```css
/* pc < 1200 */
@media screen and (max-width: 1200px) {
  .pc-max\:justify-content-start,
  .hover\:pc-max\:justify-content-start:hover {
    justify-content: flex-start;
  }
  .pc-max\:justify-content-end,
  .hover\:pc-max\:justify-content-end:hover {
    justify-content: flex-end;
  }
  .pc-max\:justify-content-center,
  .hover\:pc-max\:justify-content-center:hover {
    justify-content: center;
  }
  .pc-max\:justify-content-between,
  .hover\:pc-max\:justify-content-between:hover {
    justify-content: space-between;
  }
  .pc-max\:justify-content-around,
  .hover\:pc-max\:justify-content-around:hover {
    justify-content: space-around;
  }
}
```

# Justify Items

The CSS justify-items property defines the default justify-self for all items of the box, giving them all a default way of justifying each box along the appropriate axis.

- .justify-items-center
- .hover:justify-items-center
- .justify-items-start
- .hover:justify-items-start
- .justify-items-end
- .hover:justify-items-end
- .justify-items-stretch
- .hover:justify-items-stretch

```css
.justify-items-center,
.hover\:justify-items-center:hover {
  justify-items: center;
}
.justify-items-start,
.hover\:justify-items-start:hover {
  justify-items: start;
}
.justify-items-end,
.hover\:justify-items-end:hover {
  justify-items: end;
}
.justify-items-stretch,
.hover\:justify-items-stretch:hover {
  justify-items: stretch;
}
```
