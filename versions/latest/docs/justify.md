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
