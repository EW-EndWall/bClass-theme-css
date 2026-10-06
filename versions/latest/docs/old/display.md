# Display

The display CSS property sets whether an element is treated as a block or inline box and the layout used for its children, such as flow layout, grid or flex.

- .d-none
- .hover:d-none
- .d-inline
- .hover:d-inline
- .d-block
- .hover:d-block
- .d-inline-block
- .hover:d-inline-block
- .d-flex
- .hover:d-flex
- .d-inline-flex
- .hover:d-inline-flex
- .d-contents
- .d-grid
- .d-inline-grid
- .d-table
- .d-inline-table
- .d-table-caption
- .d-table-cell
- .d-table-col
- .d-table-col-group
- .d-table-footer-group
- .d-table-header-group
- .d-table-row-group
- .d-table-row
- .d-flow-root
- .d-list-item

```css
.d-none,
.hover\:d-none:hover {
  display: none;
}
.d-inline,
.hover\:d-inline:hover {
  display: inline;
}
.d-block,
.hover\:d-block:hover {
  display: block;
}
.d-inline-block,
.hover\:d-inline-block:hover {
  display: inline-block;
}
.d-flex,
.hover\:d-flex:hover {
  display: flex;
}
.d-inline-flex,
.hover\:d-inline-flex:hover {
  display: inline-flex;
}
.d-contents {
  display: contents;
}
.d-grid {
  display: grid;
}
.d-inline-grid {
  display: inline-grid;
}
.d-table {
  display: table;
}
.d-inline-table {
  display: inline-table;
}
.d-table-caption {
  display: table-caption;
}
.d-table-cell {
  display: table-cell;
}
.d-table-col {
  display: table-column;
}
.d-table-col-group {
  display: table-column-group;
}
.d-table-footer-group {
  display: table-footer-group;
}
.d-table-header-group {
  display: table-header-group;
}
.d-table-row-group {
  display: table-row-group;
}
.d-table-row {
  display: table-row;
}
.d-flow-root {
  display: flow-root;
}
.d-list-item {
  display: list-item;
}
```

# Mobile Display

- .mobile:d-none
- .hover:mobile:d-none
- .mobile:d-inline
- .hover:mobile:d-inline
- .mobile:d-block
- .hover:mobile:d-block
- .mobile:d-inline-block
- .hover:mobile:d-inline-block
- .mobile:d-flex
- .hover:mobile:d-flex
- .mobile:d-inline-flex
- .hover:mobile:d-inline-flex
- .mobile:d-grid
- .mobile:d-inline-grid

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:d-none,
  .hover\:mobile\:d-none:hover {
    display: none;
  }
  .mobile\:d-inline,
  .hover\:mobile\:d-inline:hover {
    display: inline;
  }
  .mobile\:d-block,
  .hover\:mobile\:d-block:hover {
    display: block;
  }
  .mobile\:d-inline-block,
  .hover\:mobile\:d-inline-block:hover {
    display: inline-block;
  }
  .mobile\:d-flex,
  .hover\:mobile\:d-flex:hover {
    display: flex;
  }
  .mobile\:d-inline-flex,
  .hover\:mobile\:d-inline-flex:hover {
    display: inline-flex;
  }
  .mobile\:d-grid {
    display: grid;
  }
  .mobile\:d-inline-grid {
    display: inline-grid;
  }
}
```

# Tablet Display

- .tablet:d-none
- .hover:tablet:d-none
- .tablet:d-inline
- .hover:tablet:d-inline
- .tablet:d-block
- .hover:tablet:d-block
- .tablet:d-inline-block
- .hover:tablet:d-inline-block
- .tablet:d-flex
- .hover:tablet:d-flex
- .tablet:d-inline-flex
- .hover:tablet:d-inline-flex
- .tablet:d-grid
- .tablet:d-inline-grid

```css
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  .tablet\:d-none,
  .hover\:tablet\:d-none:hover {
    display: none;
  }
  .tablet\:d-inline,
  .hover\:tablet\:d-inline:hover {
    display: inline;
  }
  .tablet\:d-block,
  .hover\:tablet\:d-block:hover {
    display: block;
  }
  .tablet\:d-inline-block,
  .hover\:tablet\:d-inline-block:hover {
    display: inline-block;
  }
  .tablet\:d-flex,
  .hover\:tablet\:d-flex:hover {
    display: flex;
  }
  .tablet\:d-inline-flex,
  .hover\:tablet\:d-inline-flex:hover {
    display: inline-flex;
  }
  .tablet\:d-grid {
    display: grid;
  }
  .tablet\:d-inline-grid {
    display: inline-grid;
  }
}
```

# Tablet Pc Display

- .tablet-pc:d-none
- .hover:tablet-pc:d-none
- .tablet-pc:d-inline
- .hover:tablet-pc:d-inline
- .tablet-pc:d-block
- .hover:tablet-pc:d-block
- .tablet-pc:d-inline-block
- .hover:tablet-pc:d-inline-block
- .tablet-pc:d-flex
- .hover:tablet-pc:d-flex
- .tablet-pc:d-inline-flex
- .hover:tablet-pc:d-inline-flex
- .tablet-pc:d-grid
- .tablet-pc:d-inline-grid

```css
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  .tablet-pc\:d-none,
  .hover\:tablet-pc\:d-none:hover {
    display: none;
  }
  .tablet-pc\:d-inline,
  .hover\:tablet-pc\:d-inline:hover {
    display: inline;
  }
  .tablet-pc\:d-block,
  .hover\:tablet-pc\:d-block:hover {
    display: block;
  }
  .tablet-pc\:d-inline-block,
  .hover\:tablet-pc\:d-inline-block:hover {
    display: inline-block;
  }
  .tablet-pc\:d-flex,
  .hover\:tablet-pc\:d-flex:hover {
    display: flex;
  }
  .tablet-pc\:d-inline-flex,
  .hover\:tablet-pc\:d-inline-flex:hover {
    display: inline-flex;
  }
  .tablet-pc\:d-grid {
    display: grid;
  }
  .tablet-pc\:d-inline-grid {
    display: inline-grid;
  }
}
```

# Pc Display

- .pc:d-none
- .hover:pc:d-none
- .pc:d-inline
- .hover:pc:d-inline
- .pc:d-block
- .hover:pc:d-block
- .pc:d-inline-block
- .hover:pc:d-inline-block
- .pc:d-flex
- .hover:pc:d-flex
- .pc:d-inline-flex
- .hover:pc:d-inline-flex
- .pc:d-grid
- .pc:d-inline-grid

```css
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .pc\:d-none,
  .hover\:pc\:d-none:hover {
    display: none;
  }
  .pc\:d-inline,
  .hover\:pc\:d-inline:hover {
    display: inline;
  }
  .pc\:d-block,
  .hover\:pc\:d-block:hover {
    display: block;
  }
  .pc\:d-inline-block,
  .hover\:pc\:d-inline-block:hover {
    display: inline-block;
  }
  .pc\:d-flex,
  .hover\:pc\:d-flex:hover {
    display: flex;
  }
  .pc\:d-inline-flex,
  .hover\:pc\:d-inline-flex:hover {
    display: inline-flex;
  }
  .pc\:d-grid:hover {
    display: grid;
  }
  .pc\:d-inline-grid:hover {
    display: inline-grid;
  }
}
```

# Tv Display

```css
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  .tv\:d-none,
  .hover\:tv\:d-none:hover {
    display: none;
  }
  .tv\:d-inline,
  .hover\:tv\:d-inline:hover {
    display: inline;
  }
  .tv\:d-block,
  .hover\:tv\:d-block:hover {
    display: block;
  }
  .tv\:d-inline-block,
  .hover\:tv\:d-inline-block:hover {
    display: inline-block;
  }
  .tv\:d-flex,
  .hover\:tv\:d-flex:hover {
    display: flex;
  }
  .tv\:d-inline-flex,
  .hover\:tv\:d-inline-flex:hover {
    display: inline-flex;
  }
  .tv\:d-grid {
    display: grid;
  }
  .tv\:d-inline-grid {
    display: inline-grid;
  }
}
```

# Tablet Max Display

- .tablet-max:d-none
- .hover:tablet-max:d-none
- .tablet-max:d-inline
- .hover:tablet-max:d-inline
- .tablet-max:d-block
- .hover:tablet-max:d-block
- .tablet-max:d-inline-block
- .hover:tablet-max:d-inline-block
- .tablet-max:d-flex
- .hover:tablet-max:d-flex
- .tablet-max:d-inline-flex
- .hover:tablet-max:d-inline-flex
- .tablet-max:d-grid
- .tablet-max:d-inline-grid

```css
/* tablet < 768px */
@media screen and (max-width: 768px) {
  .tablet-max\:d-none,
  .hover\:tablet-max\:d-none:hover {
    display: none;
  }
  .tablet-max\:d-inline,
  .hover\:tablet-max\:d-inline:hover {
    display: inline;
  }
  .tablet-max\:d-block,
  .hover\:tablet-max\:d-block:hover {
    display: block;
  }
  .tablet-max\:d-inline-block,
  .hover\:tablet-max\:d-inline-block:hover {
    display: inline-block;
  }
  .tablet-max\:d-flex,
  .hover\:tablet-max\:d-flex:hover {
    display: flex;
  }
  .tablet-max\:d-inline-flex,
  .hover\:tablet-max\:d-inline-flex:hover {
    display: inline-flex;
  }
  .tablet-max\:d-grid {
    display: grid;
  }
  .tablet-max\:d-inline-grid {
    display: inline-grid;
  }
}
```

# Tablet Pc Max Display

- .tablet-pc-max:d-none
- .hover:tablet-pc-max:d-none
- .tablet-pc-max:d-inline
- .hover:tablet-pc-max:d-inline
- .tablet-pc-max:d-block
- .hover:tablet-pc-max:d-block
- .tablet-pc-max:d-inline-block
- .hover:tablet-pc-max:d-inline-block
- .tablet-pc-max:d-flex
- .hover:tablet-pc-max:d-flex
- .tablet-pc-max:d-inline-flex
- .hover:tablet-pc-max:d-inline-flex
- .tablet-pc-max:d-grid
- .tablet-pc-max:d-inline-grid

```css
/* tablet-pc < 992 */
@media screen and (max-width: 992px) {
  .tablet-pc-max\:d-none,
  .hover\:tablet-pc-max\:d-none:hover {
    display: none;
  }
  .tablet-pc-max\:d-inline,
  .hover\:tablet-pc-max\:d-inline:hover {
    display: inline;
  }
  .tablet-pc-max\:d-block,
  .hover\:tablet-pc-max\:d-block:hover {
    display: block;
  }
  .tablet-pc-max\:d-inline-block,
  .hover\:tablet-pc-max\:d-inline-block:hover {
    display: inline-block;
  }
  .tablet-pc-max\:d-flex,
  .hover\:tablet-pc-max\:d-flex:hover {
    display: flex;
  }
  .tablet-pc-max\:d-inline-flex,
  .hover\:tablet-pc-max\:d-inline-flex:hover {
    display: inline-flex;
  }
  .tablet-pc-max\:d-grid {
    display: grid;
  }
  .tablet-pc-max\:d-inline-grid {
    display: inline-grid;
  }
}
```

# Pc Max Display

- .pc-max:d-none
- .hover:pc-max:d-none
- .pc-max:d-inline
- .hover:pc-max:d-inline
- .pc-max:d-block
- .hover:pc-max:d-block
- .pc-max:d-inline-block
- .hover:pc-max:d-inline-block
- .pc-max:d-flex
- .hover:pc-max:d-flex
- .pc-max:d-inline-flex
- .hover:pc-max:d-inline-flex
- .pc-max:d-grid
- .pc-max:d-inline-grid

```css
/* pc < 1200 */
@media screen and (max-width: 1200px) {
  .pc-max\:d-none,
  .hover\:pc-max\:d-none:hover {
    display: none;
  }
  .pc-max\:d-inline,
  .hover\:pc-max\:d-inline:hover {
    display: inline;
  }
  .pc-max\:d-block,
  .hover\:pc-max\:d-block:hover {
    display: block;
  }
  .pc-max\:d-inline-block,
  .hover\:pc-max\:d-inline-block:hover {
    display: inline-block;
  }
  .pc-max\:d-flex,
  .hover\:pc-max\:d-flex:hover {
    display: flex;
  }
  .pc-max\:d-inline-flex,
  .hover\:pc-max\:d-inline-flex:hover {
    display: inline-flex;
  }
  .pc-max\:d-grid {
    display: grid;
  }
  .pc-max\:d-inline-grid {
    display: inline-grid;
  }
}
```

### example

```html
<div class="container">
  <p class="hover:d-none">Hello World !</p>
</div>
```
