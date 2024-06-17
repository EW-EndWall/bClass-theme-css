# Filter

The filter CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.

# Filter Blur

The blur CSS function applies a Gaussian blur to the input image. Its result is a filter function.

- .blur-0
- .hover:blur-0
- .blur-1
- .hover:blur-1
- .blur-2
- .hover:blur-2
- .blur-3
- .hover:blur-3
- .blur-4
- .hover:blur-4
- .blur-5
- .hover:blur-5

```css
.blur-0,
.hover\:blur-0:hover {
  filter: blur(0);
}
.blur-1,
.hover\:blur-1:hover {
  filter: blur(4px);
}
.blur-2,
.hover\:blur-2:hover {
  filter: blur(8px);
}
.blur-3,
.hover\:blur-3:hover {
  filter: blur(12px);
}
.blur-4,
.hover\:blur-4:hover {
  filter: blur(16px);
}
.blur-5,
.hover\:blur-5:hover {
  filter: blur(24px);
}
```

# Backdrop Filter

The backdrop-filter CSS property lets you apply graphical effects such as blurring or color shifting to the area behind an element. Because it applies to everything behind the element, to see the effect the element or its background needs to be transparent or partially transparent.

- .bg-blur-0
- .hover:bg-blur-0
- .bg-blur-1
- .hover:bg-blur-1
- .bg-blur-2
- .hover:bg-blur-2
- .bg-blur-3
- .hover:bg-blur-3
- .bg-blur-4
- .hover:bg-blur-4
- .bg-blur-5
- .hover:bg-blur-5

```css
.bg-blur-0,
.hover\:bg-blur-0:hover {
  backdrop-filter: blur(0);
}
.bg-blur-1,
.hover\:bg-blur-1:hover {
  backdrop-filter: blur(4px);
}
.bg-blur-2,
.hover\:bg-blur-2:hover {
  backdrop-filter: blur(8px);
}
.bg-blur-3,
.hover\:bg-blur-3:hover {
  backdrop-filter: blur(12px);
}
.bg-blur-4,
.hover\:bg-blur-4:hover {
  backdrop-filter: blur(16px);
}
.bg-blur-5,
.hover\:bg-blur-5:hover {
  backdrop-filter: blur(24px);
}
```
