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

# Tablet Object Fit

- .tablet:object-contain
- .hover:tablet:object-contain
- .tablet:object-cover
- .hover:tablet:object-cover
- .tablet:object-fill
- .hover:tablet:object-fill
- .tablet:object-scale
- .hover:tablet:object-scale
- .tablet:object-none
- .hover:tablet:object-none

```css
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  .tablet\:object-contain,
  .hover\:tablet\:object-contain:hover {
    object-fit: contain;
  }
  .tablet\:object-cover,
  .hover\:tablet\:object-cover:hover {
    object-fit: cover;
  }
  .tablet\:object-fill,
  .hover\:tablet\:object-fill:hover {
    object-fit: fill;
  }
  .tablet\:object-scale,
  .hover\:tablet\:object-scale:hover {
    object-fit: scale-down;
  }
  .tablet\:object-none,
  .hover\:tablet\:object-none:hover {
    object-fit: none;
  }
}
```

# Tablet Pc Object Fit

- .tablet-pc:object-contain
- .hover:tablet-pc:object-contain
- .tablet-pc:object-cover
- .hover:tablet-pc:object-cover
- .tablet-pc:object-fill
- .hover:tablet-pc:object-fill
- .tablet-pc:object-scale
- .hover:tablet-pc:object-scale
- .tablet-pc:object-none
- .hover:tablet-pc:object-none

```css
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  .tablet-pc\:object-contain,
  .hover\:tablet-pc\:object-contain:hover {
    object-fit: contain;
  }
  .tablet-pc\:object-cover,
  .hover\:tablet-pc\:object-cover:hover {
    object-fit: cover;
  }
  .tablet-pc\:object-fill,
  .hover\:tablet-pc\:object-fill:hover {
    object-fit: fill;
  }
  .tablet-pc\:object-scale,
  .hover\:tablet-pc\:object-scale:hover {
    object-fit: scale-down;
  }
  .tablet-pc\:object-none,
  .hover\:tablet-pc\:object-none:hover {
    object-fit: none;
  }
}
```

# Pc Object Fit

- .pc:object-contain
- .hover:pc:object-contain
- .pc:object-cover
- .hover:pc:object-cover
- .pc:object-fill
- .hover:pc:object-fill
- .pc:object-scale
- .hover:pc:object-scale
- .pc:object-none
- .hover:pc:object-none

```css
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .pc\:object-contain,
  .hover\:pc\:object-contain:hover {
    object-fit: contain;
  }
  .pc\:object-cover,
  .hover\:pc\:object-cover:hover {
    object-fit: cover;
  }
  .pc\:object-fill,
  .hover\:pc\:object-fill:hover {
    object-fit: fill;
  }
  .pc\:object-scale,
  .hover\:pc\:object-scale:hover {
    object-fit: scale-down;
  }
  .pc\:object-none,
  .hover\:pc\:object-none:hover {
    object-fit: none;
  }
}
```

# Tv Object Fit

- .tv:object-contain
- .hover:tv:object-contain
- .tv:object-cover
- .hover:tv:object-cover
- .tv:object-fill
- .hover:tv:object-fill
- .tv:object-scale
- .hover:tv:object-scale
- .tv:object-none
- .hover:tv:object-none

```css
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  .tv\:object-contain,
  .hover\:tv\:object-contain:hover {
    object-fit: contain;
  }
  .tv\:object-cover,
  .hover\:tv\:object-cover:hover {
    object-fit: cover;
  }
  .tv\:object-fill,
  .hover\:tv\:object-fill:hover {
    object-fit: fill;
  }
  .tv\:object-scale,
  .hover\:tv\:object-scale:hover {
    object-fit: scale-down;
  }
  .tv\:object-none,
  .hover\:tv\:object-none:hover {
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
