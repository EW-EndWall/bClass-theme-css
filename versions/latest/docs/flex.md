# Flex Glow

The flex-grow CSS property sets the flex grow factor, which specifies how much of the flex container's remaining space should be assigned to the flex item's main size.

- .flex-grow-0
- .hover:flex-grow-0
- .flex-grow-1
- .hover:flex-grow-1
- .flex-grow-2
- .hover:flex-grow-2
- .flex-grow-3
- .hover:flex-grow-3

```css
.flex-grow-0,
.hover\:flex-grow-0:hover {
  flex-grow: 0;
}
.flex-grow-1,
.hover\:flex-grow-1:hover {
  flex-grow: 1;
}
.flex-grow-2,
.hover\:flex-grow-2:hover {
  flex-grow: 2;
}
.flex-grow-3,
.hover\:flex-grow-3:hover {
  flex-grow: 3;
}
```

# Mobile Flex Wrap

- .mobile:flex-grow-0
- .hover:mobile:flex-grow-0
- .mobile:flex-grow-1
- .hover:mobile:flex-grow-1
- .mobile:flex-grow-2
- .hover:mobile:flex-grow-2
- .mobile:flex-grow-3
- .hover:mobile:flex-grow-3

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:flex-grow-0,
  .hover\:mobile\:flex-grow-0:hover {
    flex-grow: 0;
  }
  .mobile\:flex-grow-1,
  .hover\:mobile\:flex-grow-1:hover {
    flex-grow: 1;
  }
  .mobile\:flex-grow-2,
  .hover\:mobile\:flex-grow-2:hover {
    flex-grow: 2;
  }
  .mobile\:flex-grow-3,
  .hover\:mobile\:flex-grow-3:hover {
    flex-grow: 3;
  }
}
```

# Flex Direction

The flex-direction CSS property sets how flex items are placed in the flex container defining the main axis and the direction (normal or reversed).

- .flex-row
- .hover:flex-row
- .flex-row-reverse
- .hover:flex-row-reverse
- .flex-col
- .hover:flex-col
- .flex-col-reverse
- .hover:flex-col-reverse

```css
.flex-row,
.hover\:flex-row:hover {
  flex-direction: row;
}
.flex-row-reverse,
.hover\:flex-row-reverse:hover {
  flex-direction: row-reverse;
}
.flex-col,
.hover\:flex-col:hover {
  flex-direction: column;
}
.flex-col-reverse,
.hover\:flex-col-reverse:hover {
  flex-direction: column-reverse;
}
```

# Mobile Flex Direction

- .mobile:flex-row
- .hover:mobile:flex-row
- .mobile:flex-row-reverse
- .hover:mobile:flex-row-reverse
- .mobile:flex-col
- .hover:mobile:flex-col
- .mobile:flex-col-reverse
- .hover:mobile:flex-col-reverse

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:flex-row,
  .hover\:mobile\:flex-row:hover {
    flex-direction: row;
  }
  .mobile\:flex-row-reverse,
  .hover\:mobile\:flex-row-reverse:hover {
    flex-direction: row-reverse;
  }
  .mobile\:flex-col,
  .hover\:mobile\:flex-col:hover {
    flex-direction: column;
  }
  .mobile\:flex-col-reverse,
  .hover\:mobile\:flex-col-reverse:hover {
    flex-direction: column-reverse;
  }
}
```

# Flex Wrap

The flex-wrap CSS property sets whether flex items are forced onto one line or can wrap onto multiple lines. If wrapping is allowed, it sets the direction that lines are stacked.

- .flex-nowrap
- .hover:flex-nowrap
- .flex-wrap
- .hover:flex-wrap
- .flex-wrap-reverse
- .hover:flex-wrap-reverse

```css
.flex-nowrap,
.hover\:flex-nowrap:hover {
  flex-wrap: nowrap;
}
.flex-wrap,
.hover\:flex-wrap:hover {
  flex-wrap: wrap;
}
.flex-wrap-reverse,
.hover\:flex-wrap-reverse:hover {
  flex-wrap: wrap-reverse;
}
```

# Mobile Flex Wrap

- .mobile:flex-nowrap
- .hover:mobile:flex-nowrap
- .mobile:flex-wrap
- .hover:mobile:flex-wrap
- .mobile:flex-wrap-reverse
- .hover:mobile:flex-wrap-reverse

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:flex-nowrap,
  .hover\:mobile\:flex-nowrap:hover {
    flex-wrap: nowrap;
  }
  .mobile\:flex-wrap,
  .hover\:mobile\:flex-wrap:hover {
    flex-wrap: wrap;
  }
  .mobile\:flex-wrap-reverse,
  .hover\:mobile\:flex-wrap-reverse:hover {
    flex-wrap: wrap-reverse;
  }
}
```
