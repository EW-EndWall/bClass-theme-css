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

# Mobile Object Fit

- .mobile:object-contain
- .hover:mobile:object-contain
- .mobile:object-cover
- .hover:mobile:object-cover
- .mobile:object-fill
- .hover:mobile:object-fill
- .mobile:object-scale
- .hover:mobile:object-scale
- .mobile:object-none
- .hover:mobile:object-none

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:object-contain,
  .hover\:mobile\:object-contain:hover {
    object-fit: contain;
  }
  .mobile\:object-cover,
  .hover\:mobile\:object-cover:hover {
    object-fit: cover;
  }
  .mobile\:object-fill,
  .hover\:mobile\:object-fill:hover {
    object-fit: fill;
  }
  .mobile\:object-scale,
  .hover\:mobile\:object-scale:hover {
    object-fit: scale-down;
  }
  .mobile\:object-none,
  .hover\:mobile\:object-none:hover {
    object-fit: none;
  }
}
```

### example

```html
<div class="container">
  <img src="./img.png" class="object-cover">Hello World !</img>
</div>
```
