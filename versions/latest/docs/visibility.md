# Visibility

The visibility CSS property shows or hides an element without changing the layout of a document.

- .v-show
- .hover:v-show
- .v-hide
- .hover:v-hide

```css
.v-show,
.hover\:v-show:hover {
  visibility: visible;
}
.v-hide,
.hover\:v-hide:hover {
  visibility: hidden;
}
```

# Mobile Visibility

- .mobile:v-show
- .hover:mobile:v-show
- .mobile:v-hide
- .hover:mobile:v-hide

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:v-show,
  .hover\:mobile\:v-show:hover {
    visibility: visible;
  }
  .mobile\:v-hide,
  .hover\:mobile\:v-hide:hover {
    visibility: hidden;
  }
}
```

### example

```html
<div class="container">
  <p class="hover:v-hide">Hello World !</p>
</div>
```
