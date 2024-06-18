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

### example

```html
<div class="container">
  <p class="hover:d-none">Hello World !</p>
</div>
```
