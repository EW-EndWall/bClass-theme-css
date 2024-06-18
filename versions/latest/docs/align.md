# Align Items

The CSS align-items property sets the align-self value on all direct children as a group. In Flexbox, it controls the alignment of items on the Cross Axis. In Grid Layout, it controls the alignment of items on the Block Axis within their grid area.

- .align-items-start
- .hover:align-items-start
- .align-items-end
- .hover:align-items-end
- .align-items-center
- .hover:align-items-center
- .align-items-stretch
- .hover:align-items-stretch

```css
.align-items-start,
.hover\:align-items-start:hover {
  align-items: flex-start;
}
.align-items-end,
.hover\:align-items-end:hover {
  align-items: flex-end;
}
.align-items-center,
.hover\:align-items-center:hover {
  align-items: center;
}
.align-items-stretch,
.hover\:align-items-stretch:hover {
  align-items: stretch;
}
```

# Mobile Align Items

- .mobile:align-items-start
- .hover:mobile:align-items-start
- .mobile:align-items-end
- .hover:mobile:align-items-end
- .mobile:align-items-center
- .hover:mobile:align-items-center
- .mobile:align-items-stretch
- .hover:mobile:align-items-stretch

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:align-items-start,
  .hover\:mobile\:align-items-start:hover {
    align-items: flex-start;
  }
  .mobile\:align-items-end,
  .hover\:mobile\:align-items-end:hover {
    align-items: flex-end;
  }
  .mobile\:align-items-center,
  .hover\:mobile\:align-items-center:hover {
    align-items: center;
  }
  .mobile\:align-items-stretch,
  .hover\:mobile\:align-items-stretch:hover {
    align-items: stretch;
  }
}
```

# Align Self

The align-self CSS property overrides a grid or flex item's align-items value. In Grid, it aligns the item inside the grid area. In Flexbox, it aligns the item on the cross axis.

- .align-self-start
- .hover:align-self-start
- .align-self-end
- .hover:align-self-end
- .align-self-center
- .hover:align-self-center
- .align-self-stretch
- .hover:align-self-stretch

```css
.align-self-start,
.hover\:align-self-start:hover {
  align-self: start;
}
.align-self-end,
.hover\:align-self-end:hover {
  align-self: end;
}
.align-self-center,
.hover\:align-self-center:hover {
  align-self: center;
}
.align-self-stretch,
.hover\:align-self-stretch:hover {
  align-self: stretch;
}
```

# Mobile Align Self

- .mobile:align-self-start
- .hover:mobile:align-self-start
- .mobile:align-self-end
- .hover:mobile:align-self-end
- .mobile:align-self-center
- .hover:mobile:align-self-center
- .mobile:align-self-stretch
- .hover:mobile:align-self-stretch

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:align-self-start,
  .hover\:mobile\:align-self-start:hover {
    align-self: start;
  }
  .mobile\:align-self-end,
  .hover\:mobile\:align-self-end:hover {
    align-self: end;
  }
  .mobile\:align-self-center,
  .hover\:mobile\:align-self-center:hover {
    align-self: center;
  }
  .mobile\:align-self-stretch,
  .hover\:mobile\:align-self-stretch:hover {
    align-self: stretch;
  }
}
```

# Align Content

The CSS align-content property sets the distribution of space between and around content items along a flexbox's cross axis, or a grid or block-level element's block axis.

- .align-content-start
- .hover:align-content-start
- .align-content-end
- .hover:align-content-end
- .align-content-center
- .hover:align-content-center
- .align-content-around
- .hover:align-content-around
- .align-content-stretch
- .hover:align-content-stretch
- .align-content-between
- .hover:align-content-between
- .align-content-evenly
- .hover:align-content-evenly

```css
.align-content-start,
.hover\:align-content-start:hover {
  align-content: flex-start;
}
.align-content-end,
.hover\:align-content-end:hover {
  align-content: flex-end;
}
.align-content-center,
.hover\:align-content-center:hover {
  align-content: center;
}
.align-content-around,
.hover\:align-content-around:hover {
  align-content: space-around;
}
.align-content-stretch,
.hover\:align-content-stretch:hover {
  align-content: stretch;
}
.align-content-between,
.hover\:align-content-between:hover {
  align-content: space-between;
}
.align-content-evenly,
.hover\:align-content-evenly:hover {
  align-content: space-evenly;
}
```

# Mobile Align Content

- .mobile:align-content-start
- .hover:mobile:align-content-start
- .mobile:align-content-end
- .hover:mobile:align-content-end
- .mobile:align-content-center
- .hover:mobile:align-content-center
- .mobile:align-content-around
- .hover:mobile:align-content-around
- .mobile:align-content-stretch
- .hover:mobile:align-content-stretch
- .mobile:align-content-between
- .hover:mobile:align-content-between
- .mobile:align-content-evenly
- .hover:mobile:align-content-evenly

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:align-content-start,
  .hover\:mobile\:align-content-start:hover {
    align-content: flex-start;
  }
  .mobile\:align-content-end,
  .hover\:mobile\:align-content-end:hover {
    align-content: flex-end;
  }
  .mobile\:align-content-center,
  .hover\:mobile\:align-content-center:hover {
    align-content: center;
  }
  .mobile\:align-content-around,
  .hover\:mobile\:align-content-around:hover {
    align-content: space-around;
  }
  .mobile\:align-content-stretch,
  .hover\:mobile\:align-content-stretch:hover {
    align-content: stretch;
  }
  .mobile\:align-content-between,
  .hover\:mobile\:align-content-between:hover {
    align-content: space-between;
  }
  .mobile\:align-content-evenly,
  .hover\:mobile\:align-content-evenly:hover {
    align-content: space-evenly;
  }
}
```
