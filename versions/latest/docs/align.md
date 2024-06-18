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

# Tablet Align Items

- .tablet:align-items-start
- .hover:tablet:align-items-start
- .tablet:align-items-end
- .hover:tablet:align-items-end
- .tablet:align-items-center
- .hover:tablet:align-items-center
- .tablet:align-items-stretch
- .hover:tablet:align-items-stretch

```css
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  .tablet\:align-items-start,
  .hover\:tablet\:align-items-start:hover {
    align-items: flex-start;
  }
  .tablet\:align-items-end,
  .hover\:tablet\:align-items-end:hover {
    align-items: flex-end;
  }
  .tablet\:align-items-center,
  .hover\:tablet\:align-items-center:hover {
    align-items: center;
  }
  .tablet\:align-items-stretch,
  .hover\:tablet\:align-items-stretch:hover {
    align-items: stretch;
  }
}
```

# Tablet Pc Align Items

- .tablet-pc:align-items-start
- .hover:tablet-pc:align-items-start
- .tablet-pc:align-items-end
- .hover:tablet-pc:align-items-end
- .tablet-pc:align-items-center
- .hover:tablet-pc:align-items-center
- .tablet-pc:align-items-stretch
- .hover:tablet-pc:align-items-stretch

```css
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  .tablet-pc\:align-items-start,
  .hover\:tablet-pc\:align-items-start:hover {
    align-items: flex-start;
  }
  .tablet-pc\:align-items-end,
  .hover\:tablet-pc\:align-items-end:hover {
    align-items: flex-end;
  }
  .tablet-pc\:align-items-center,
  .hover\:tablet-pc\:align-items-center:hover {
    align-items: center;
  }
  .tablet-pc\:align-items-stretch,
  .hover\:tablet-pc\:align-items-stretch:hover {
    align-items: stretch;
  }
}
```

# Pc Align Items

- .pc:align-items-start
- .hover:pc:align-items-start
- .pc:align-items-end
- .hover:pc:align-items-end
- .pc:align-items-center
- .hover:pc:align-items-center
- .pc:align-items-stretch
- .hover:pc:align-items-stretch

```css
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .pc\:align-items-start,
  .hover\:pc\:align-items-start:hover {
    align-items: flex-start;
  }
  .pc\:align-items-end,
  .hover\:pc\:align-items-end:hover {
    align-items: flex-end;
  }
  .pc\:align-items-center,
  .hover\:pc\:align-items-center:hover {
    align-items: center;
  }
  .pc\:align-items-stretch,
  .hover\:pc\:align-items-stretch:hover {
    align-items: stretch;
  }
}
```

# Tv Align Items

- .tv:align-items-start
- .hover:tv:align-items-start
- .tv:align-items-end
- .hover:tv:align-items-end
- .tv:align-items-center
- .hover:tv:align-items-center
- .tv:align-items-stretch
- .hover:tv:align-items-stretch

```css
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  .tv\:align-items-start,
  .hover\:tv\:align-items-start:hover {
    align-items: flex-start;
  }
  .tv\:align-items-end,
  .hover\:tv\:align-items-end:hover {
    align-items: flex-end;
  }
  .tv\:align-items-center,
  .hover\:tv\:align-items-center:hover {
    align-items: center;
  }
  .tv\:align-items-stretch,
  .hover\:tv\:align-items-stretch:hover {
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

# Tablet Align Self

- .tablet:align-self-start
- .hover:tablet:align-self-start
- .tablet:align-self-end
- .hover:tablet:align-self-end
- .tablet:align-self-center
- .hover:tablet:align-self-center
- .tablet:align-self-stretch
- .hover:tablet:align-self-stretch

```css
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  .tablet\:align-self-start,
  .hover\:tablet\:align-self-start:hover {
    align-self: start;
  }
  .tablet\:align-self-end,
  .hover\:tablet\:align-self-end:hover {
    align-self: end;
  }
  .tablet\:align-self-center,
  .hover\:tablet\:align-self-center:hover {
    align-self: center;
  }
  .tablet\:align-self-stretch,
  .hover\:tablet\:align-self-stretch:hover {
    align-self: stretch;
  }
}
```

# Tablet Pc Align Self

- .tablet-pc:align-self-start
- .hover:tablet-pc:align-self-start
- .tablet-pc:align-self-end
- .hover:tablet-pc:align-self-end
- .tablet-pc:align-self-center
- .hover:tablet-pc:align-self-center
- .tablet-pc:align-self-stretch
- .hover:tablet-pc:align-self-stretch

```css
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  .tablet-pc\:align-self-start,
  .hover\:tablet-pc\:align-self-start:hover {
    align-self: start;
  }
  .tablet-pc\:align-self-end,
  .hover\:tablet-pc\:align-self-end:hover {
    align-self: end;
  }
  .tablet-pc\:align-self-center,
  .hover\:tablet-pc\:align-self-center:hover {
    align-self: center;
  }
  .tablet-pc\:align-self-stretch,
  .hover\:tablet-pc\:align-self-stretch:hover {
    align-self: stretch;
  }
}
```

# Pc Align Self

- .pc:align-self-start
- .hover:pc:align-self-start
- .pc:align-self-end
- .hover:pc:align-self-end
- .pc:align-self-center
- .hover:pc:align-self-center
- .pc:align-self-stretch
- .hover:pc:align-self-stretch

```css
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .pc\:align-self-start,
  .hover\:pc\:align-self-start:hover {
    align-self: start;
  }
  .pc\:align-self-end,
  .hover\:pc\:align-self-end:hover {
    align-self: end;
  }
  .pc\:align-self-center,
  .hover\:pc\:align-self-center:hover {
    align-self: center;
  }
  .pc\:align-self-stretch,
  .hover\:pc\:align-self-stretch:hover {
    align-self: stretch;
  }
```

# Tv Align Self

- .tv:align-self-start
- .hover:tv:align-self-start
- .tv:align-self-end
- .hover:tv:align-self-end
- .tv:align-self-center
- .hover:tv:align-self-center
- .tv:align-self-stretch
- .hover:tv:align-self-stretch

```css
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  .tv\:align-self-start,
  .hover\:tv\:align-self-start:hover {
    align-self: start;
  }
  .tv\:align-self-end,
  .hover\:tv\:align-self-end:hover {
    align-self: end;
  }
  .tv\:align-self-center,
  .hover\:tv\:align-self-center:hover {
    align-self: center;
  }
  .tv\:align-self-stretch,
  .hover\:tv\:align-self-stretch:hover {
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

# Tablet Align Content

- .tablet:align-content-start
- .hover:tablet:align-content-start
- .tablet:align-content-end
- .hover:tablet:align-content-end
- .tablet:align-content-center
- .hover:tablet:align-content-center
- .tablet:align-content-around
- .hover:tablet:align-content-around
- .tablet:align-content-stretch
- .hover:tablet:align-content-stretch
- .tablet:align-content-between
- .hover:tablet:align-content-between
- .tablet:align-content-evenly
- .hover:tablet:align-content-evenly

```css
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  .tablet\:align-content-start,
  .hover\:tablet\:align-content-start:hover {
    align-content: flex-start;
  }
  .tablet\:align-content-end,
  .hover\:tablet\:align-content-end:hover {
    align-content: flex-end;
  }
  .tablet\:align-content-center,
  .hover\:tablet\:align-content-center:hover {
    align-content: center;
  }
  .tablet\:align-content-around,
  .hover\:tablet\:align-content-around:hover {
    align-content: space-around;
  }
  .tablet\:align-content-stretch,
  .hover\:tablet\:align-content-stretch:hover {
    align-content: stretch;
  }
  .tablet\:align-content-between,
  .hover\:tablet\:align-content-between:hover {
    align-content: space-between;
  }
  .tablet\:align-content-evenly,
  .hover\:tablet\:align-content-evenly:hover {
    align-content: space-evenly;
  }
}
```

# Tablet Pc Align Content

- .tablet-pc:align-content-start
- .hover:tablet-pc:align-content-start
- .tablet-pc:align-content-end
- .hover:tablet-pc:align-content-end
- .tablet-pc:align-content-center
- .hover:tablet-pc:align-content-center
- .tablet-pc:align-content-around
- .hover:tablet-pc:align-content-around
- .tablet-pc:align-content-stretch
- .hover:tablet-pc:align-content-stretch
- .tablet-pc:align-content-between
- .hover:tablet-pc:align-content-between
- .tablet-pc:align-content-evenly
- .hover:tablet-pc:align-content-evenly

```css
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  .tablet-pc\:align-content-start,
  .hover\:tablet-pc\:align-content-start:hover {
    align-content: flex-start;
  }
  .tablet-pc\:align-content-end,
  .hover\:tablet-pc\:align-content-end:hover {
    align-content: flex-end;
  }
  .tablet-pc\:align-content-center,
  .hover\:tablet-pc\:align-content-center:hover {
    align-content: center;
  }
  .tablet-pc\:align-content-around,
  .hover\:tablet-pc\:align-content-around:hover {
    align-content: space-around;
  }
  .tablet-pc\:align-content-stretch,
  .hover\:tablet-pc\:align-content-stretch:hover {
    align-content: stretch;
  }
  .tablet-pc\:align-content-between,
  .hover\:tablet-pc\:align-content-between:hover {
    align-content: space-between;
  }
  .tablet-pc\:align-content-evenly,
  .hover\:tablet-pc\:align-content-evenly:hover {
    align-content: space-evenly;
  }
}
```

# Pc Align Content

- .pc:align-content-start
- .hover:pc:align-content-start
- .pc:align-content-end
- .hover:pc:align-content-end
- .pc:align-content-center
- .hover:pc:align-content-center
- .pc:align-content-around
- .hover:pc:align-content-around
- .pc:align-content-stretch
- .hover:pc:align-content-stretch
- .pc:align-content-between
- .hover:pc:align-content-between
- .pc:align-content-evenly
- .hover:pc:align-content-evenly

```css
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .pc\:align-content-start,
  .hover\:pc\:align-content-start:hover {
    align-content: flex-start;
  }
  .pc\:align-content-end,
  .hover\:pc\:align-content-end:hover {
    align-content: flex-end;
  }
  .pc\:align-content-center,
  .hover\:pc\:align-content-center:hover {
    align-content: center;
  }
  .pc\:align-content-around,
  .hover\:pc\:align-content-around:hover {
    align-content: space-around;
  }
  .pc\:align-content-stretch,
  .hover\:pc\:align-content-stretch:hover {
    align-content: stretch;
  }
  .pc\:align-content-between,
  .hover\:pc\:align-content-between:hover {
    align-content: space-between;
  }
  .pc\:align-content-evenly,
  .hover\:pc\:align-content-evenly:hover {
    align-content: space-evenly;
  }
}
```

# Tv Align Content

- .tv:align-content-start
- .hover:tv:align-content-start
- .tv:align-content-end
- .hover:tv:align-content-end
- .tv:align-content-center
- .hover:tv:align-content-center
- .tv:align-content-around
- .hover:tv:align-content-around
- .tv:align-content-stretch
- .hover:tv:align-content-stretch
- .tv:align-content-between
- .hover:tv:align-content-between
- .tv:align-content-evenly
- .hover:tv:align-content-evenly

```css
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  .tv\:align-content-start,
  .hover\:tv\:align-content-start:hover {
    align-content: flex-start;
  }
  .tv\:align-content-end,
  .hover\:tv\:align-content-end:hover {
    align-content: flex-end;
  }
  .tv\:align-content-center,
  .hover\:tv\:align-content-center:hover {
    align-content: center;
  }
  .tv\:align-content-around,
  .hover\:tv\:align-content-around:hover {
    align-content: space-around;
  }
  .tv\:align-content-stretch,
  .hover\:tv\:align-content-stretch:hover {
    align-content: stretch;
  }
  .tv\:align-content-between,
  .hover\:tv\:align-content-between:hover {
    align-content: space-between;
  }
  .tv\:align-content-evenly,
  .hover\:tv\:align-content-evenly:hover {
    align-content: space-evenly;
  }
}
```
