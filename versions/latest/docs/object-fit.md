# Object Fit

The object-fit CSS property sets how the content of a replaced element, such as an <img> or <video>, should be resized to fit its container.

- .object-contain
- .hover:object-contain
- .object-cover
- .hover:object-cover
- .object-fill,
- .hover:object-fill
- .object-scale
- .hover:object-scale
- .object-none
- .hover:object-none

```css
.object-contain,
.hover\:object-contain:hover {
  object-fit: contain;
}
.object-cover,
.hover\:object-cover:hover {
  object-fit: cover;
}
.object-fill,
.hover\:object-fill:hover {
  object-fit: fill;
}
.object-scale,
.hover\:object-scale:hover {
  object-fit: scale-down;
}
.object-none,
.hover\:object-none:hover {
  object-fit: none;
}
```

### example

```html
<div class="container">
  <img src="./img.png" class="object-cover">Hello World !</img>
</div>
```
