# Overflow

The overflow CSS shorthand property sets the desired behavior when content does not fit in the element's padding box (overflows) in the horizontal and/or vertical direction.

- .overflow-auto
- .overflow-x-auto
- .overflow-auto
- .overflow-y-auto
- .overflow-hidden
- .overflow-y-hidden
- .overflow-hidden
- .overflow-x-hidden
- .overflow-clip
- .overflow-x-clip
- .overflow-clip
- .overflow-y-clip
- .overflow-visible
- .overflow-x-visible
- .overflow-visible
- .overflow-y-visible
- .overflow-scroll
- .overflow-x-scroll
- .hover:overflow-scroll
- .hover:overflow-x-scroll
- .overflow-scroll
- .overflow-y-scroll
- .hover:overflow-scroll
- .hover:overflow-y-scroll

```css
.overflow-auto,
.overflow-x-auto {
  overflow-x: auto;
}
.overflow-auto,
.overflow-y-auto {
  overflow-y: auto;
}
.overflow-hidden,
.overflow-y-hidden {
  overflow-y: hidden;
}
.overflow-hidden,
.overflow-x-hidden {
  overflow-x: hidden;
}
.overflow-clip,
.overflow-x-clip {
  overflow-x: clip;
}
.overflow-clip,
.overflow-y-clip {
  overflow-y: clip;
}
.overflow-visible,
.overflow-x-visible {
  overflow-x: visible;
}
.overflow-visible,
.overflow-y-visible {
  overflow-y: visible;
}
.overflow-scroll,
.overflow-x-scroll,
.hover\:overflow-scroll:hover,
.hover\:overflow-x-scroll:hover {
  overflow-x: scroll;
}
.overflow-scroll,
.overflow-y-scroll,
.hover\:overflow-scroll:hover,
.hover\:overflow-y-scroll:hover {
  overflow-y: scroll;
}
```

### example

```html
<div class="container">
  <div class="overflow-x-scroll">Hello World !</div>
</div>
```
