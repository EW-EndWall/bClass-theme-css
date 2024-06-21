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

# Tablet Visibility

.tablet:v-show
.hover:tablet:v-show
.tablet:v-hide
.hover:tablet:v-hide

```css
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  .tablet\:v-show,
  .hover\:tablet\:v-show:hover {
    visibility: visible;
  }
  .tablet\:v-hide,
  .hover\:tablet\:v-hide:hover {
    visibility: hidden;
  }
}
```

# Tablet Pc Visibility

- .tablet-pc:v-show
- .hover:tablet-pc:v-show
- .tablet-pc:v-hide
- .hover:tablet-pc:v-hide

```css
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  .tablet-pc\:v-show,
  .hover\:tablet-pc\:v-show:hover {
    visibility: visible;
  }
  .tablet-pc\:v-hide,
  .hover\:tablet-pc\:v-hide:hover {
    visibility: hidden;
  }
}
```

# Pc Visibility

- .pc:v-show
- .hover:pc:v-show
- .pc:v-hide
- .hover:pc:v-hide

```css
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .pc\:v-show,
  .hover\:pc\:v-show:hover {
    visibility: visible;
  }
  .pc\:v-hide,
  .hover\:pc\:v-hide:hover {
    visibility: hidden;
  }
}
```

# Tv Visibility

- .tv:v-show
- .hover:tv:v-show
- .tv:v-hide
- .hover:tv:v-hide

```css
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  .tv\:v-show,
  .hover\:tv\:v-show:hover {
    visibility: visible;
  }
  .tv\:v-hide,
  .hover\:tv\:v-hide:hover {
    visibility: hidden;
  }
}
```

# Tablet Max Visibility

- .tablet-max:v-show
- .hover:tablet-max:v-show
- .tablet-max:v-hide
- .hover:tablet-max:v-hide

```css
/* tablet < 768px */
@media screen and (max-width: 768px) {
  .tablet-max\:v-show,
  .hover\:tablet-max\:v-show:hover {
    visibility: visible;
  }
  .tablet-max\:v-hide,
  .hover\:tablet-max\:v-hide:hover {
    visibility: hidden;
  }
}
```

# Tablet Pc Max Visibility

- .tablet-pc-max\:v-show
- .hover:tablet-pc-max:v-show
- .tablet-pc-max:v-hide
- .hover:tablet-pc-max:v-hide

```css
/* tablet-pc < 992 */
@media screen and (max-width: 992px) {
  .tablet-pc-max\:v-show,
  .hover\:tablet-pc-max\:v-show:hover {
    visibility: visible;
  }
  .tablet-pc-max\:v-hide,
  .hover\:tablet-pc-max\:v-hide:hover {
    visibility: hidden;
  }
}
```

# Pc Max Visibility

- .pc-max:v-show
- .hover:pc-max:v-show
- .pc-max:v-hide
- .hover:pc-max:v-hide

```css
/* pc < 1200 */
@media screen and (max-width: 1200px) {
  .pc-max\:v-show,
  .hover\:pc-max\:v-show:hover {
    visibility: visible;
  }
  .pc-max\:v-hide,
  .hover\:pc-max\:v-hide:hover {
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
