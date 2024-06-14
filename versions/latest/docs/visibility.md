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

### example

```html
<div class="container">
  <p class="hover:v-hide">Hello World !</p>
</div>
```
