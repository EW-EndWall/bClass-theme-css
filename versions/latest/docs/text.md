# Text Classes

## Text Decoration

The text-decoration shorthand CSS property sets the appearance of decorative lines on text.

- .text-line-none
- .hover:text-line-none
- .text-line-underline
- .hover:text-line-underline
- .text-line-overline
- .hover:text-line-overline
- .text-line-through
- .hover:text-line-through

```css
.text-line-none,
.hover\:text-line-none:hover {
  text-decoration: none;
}
.text-line-underline,
.hover\:text-line-underline:hover {
  text-decoration-line: underline;
}
.text-line-overline,
.hover\:text-line-overline:hover {
  text-decoration: overline;
}
.text-line-through,
.hover\:text-line-through:hover {
  text-decoration: line-through;
}
```

## Writing Mode

The writing-mode CSS property sets whether lines of text are laid out horizontally or vertically, as well as the direction in which blocks progress. When set for an entire document, it should be set on the root element (html element for HTML documents).

- .writing-h-tb
- .writing-v-lr
- .writing-v-rl

```css
.writing-h-tb {
  writing-mode: horizontal-tb;
}
.writing-v-lr {
  writing-mode: vertical-lr;
}
.writing-v-rl {
  writing-mode: vertical-rl;
}
```

## Direction

The direction CSS property sets the direction of text, table columns, and horizontal overflow. Use rtl for languages written from right to left (like Hebrew or Arabic), and ltr for those written from left to right (like English and most other languages).

- .dir-ltr
- .dir-rtl

```css
.dir-ltr {
  direction: ltr;
}
.dir-rtl {
  direction: rtl;
}
```

## Word Break

The word-break CSS property sets whether line breaks appear wherever the text would otherwise overflow its content box.

- .text-break-normal
- .text-break-all
- .text-break-keep-all
- .text-break-word

```css
.text-break-normal {
  word-break: normal;
  overflow-wrap: normal;
}
.text-break-all {
  word-break: break-all;
}
.text-break-keep-all {
  word-break: keep-all;
}
.text-break-word {
  word-break: break-word;
}
```

## Text Overflow

The text-overflow CSS property sets how hidden overflow content is signaled to users.

- .text-overflow-ellipsis
- .text-overflow-clip

```css
.text-overflow-ellipsis {
  text-overflow: ellipsis;
}
.text-overflow-clip {
  text-overflow: clip;
}
```

## White Space

The white-space CSS property sets how white space inside an element is handled.

- .whitespace-normal
- .hover:whitespace-normal
- .whitespace-nowrap
- .whitespace-pre
- .whitespace-pre-line
- .hover:whitespace-pre-line
- .whitespace-pre-wrap
- .hover:whitespace-pre-wrap
- .whitespace-break-spaces
- .hover:whitespace-break-spaces

```css
.whitespace-normal,
.hover\:whitespace-normal:hover {
  white-space: normal;
}
.whitespace-nowrap {
  white-space: nowrap;
}
.whitespace-pre {
  white-space: pre;
}
.whitespace-pre-line,
.hover\:whitespace-pre-line:hover {
  white-space: pre-line;
}
.whitespace-pre-wrap,
.hover\:whitespace-pre-wrap:hover {
  white-space: pre-wrap;
}
.whitespace-break-spaces,
.hover\:whitespace-break-spaces:hover {
  white-space: break-spaces;
}
```

## Content Text

The content-1-text CSS data type represents a color.

- .content-1-text
- .hover:content-1-text
- .content-2-text
- .hover:content-2-text

```css
.content-1-text,
.hover\:content-1-text:hover {
  color: var(--contentTextPrimary);
}
.content-2-text,
.hover\:content-2-text:hover {
  color: var(--contentTextSecondary);
}
```

## Font Weight

The font-weight CSS property sets the weight (or boldness) of the font. The weights available depend on the font-family that is currently set.

- .font-weight-100
- .hover:font-weight-100
- .font-weight-300
- .hover:font-weight-300
- .font-weight-200
- .hover:font-weight-200
- .font-weight-400
- .hover:font-weight-400
- .font-weight-500
- .hover:font-weight-500
- .font-weight-600
- .hover:font-weight-600
- .font-weight-700
- .font-weight-bold
- .hover:font-weight-700
- .hover:font-weight-bold
- .font-weight-800
- .hover:font-weight-800
- .font-weight-900
- .hover:font-weight-900

```css
.font-weight-100,
.hover\:font-weight-100:hover {
  font-weight: 100;
}
.font-weight-300,
.hover\:font-weight-300:hover {
  font-weight: 300;
}
.font-weight-200,
.hover\:font-weight-200:hover {
  font-weight: 200;
}
.font-weight-400,
.hover\:font-weight-400:hover {
  font-weight: 400;
}
.font-weight-500,
.hover\:font-weight-500:hover {
  font-weight: 500;
}
.font-weight-600,
.hover\:font-weight-600:hover {
  font-weight: 600;
}
.font-weight-700,
.font-weight-bold,
.hover\:font-weight-700:hover,
.hover\:font-weight-bold:hover {
  font-weight: 700;
}
.font-weight-800,
.hover\:font-weight-800:hover {
  font-weight: 800;
}
.font-weight-900,
.hover\:font-weight-900:hover {
  font-weight: 900;
}
```

## Font Style

The font-style CSS property sets whether a font should be styled with a normal or italic face from its font-family.

- .font-normal
- .hover:font-normal
- .font-italic
- .hover:font-italic

```css
.font-normal,
.hover\:font-normal:hover {
  font-style: normal;
}
.font-italic,
.hover\:font-italic:hover {
  font-style: italic;
}
```

## Text Transform

The text-transform CSS property specifies how to capitalize an element's text. It can be used to make text appear in all-uppercase or all-lowercase, or with each word capitalized. It also can help improve legibility for ruby.

- .text-lowercase
- .hover:text-lowercase
- .text-uppercase
- .hover:text-uppercase
- .text-capitalize
- .hover:text-capitalize

```css
.text-lowercase,
.hover\:text-lowercase:hover {
  text-transform: lowercase;
}
.text-uppercase,
.hover\:text-uppercase:hover {
  text-transform: uppercase;
}
.text-capitalize,
.hover\:text-capitalize:hover {
  text-transform: capitalize;
}
```

## Text Align

The text-align CSS property sets the horizontal alignment of the inline-level content inside a block element or table-cell box. This means it works like vertical-align but in the horizontal direction.

- .text-right
- .hover:text-right
- .text-left
- .hover:text-left
- .text-center
- .hover:text-center
- .text-justify
- .hover:text-justify
- .text-start
- .hover:text-start
- .text-end
- .hover:text-end

```css
.text-right,
.hover\:text-right:hover {
  text-align: right;
}
.text-left,
.hover\:text-left:hover {
  text-align: left;
}
.text-center,
.hover\:text-center:hover {
  text-align: center;
}
.text-justify,
.hover\:text-justify:hover {
  text-align: justify;
}
.text-start,
.hover\:text-start:hover {
  text-align: start;
}
.text-end,
.hover\:text-end:hover {
  text-align: end;
}
```

# Mobile Text Align

- .mobile:text-right
- .hover:mobile:text-right
- .mobile:text-left
- .hover:mobile:text-left
- .mobile:text-center
- .hover:mobile:text-center
- .mobile:text-justify
- .hover:mobile:text-justify
- .mobile:text-start
- .hover:mobile:text-start
- .mobile:text-end
- .hover:mobile:text-end

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  .mobile\:text-right,
  .hover\:mobile\:text-right:hover {
    text-align: right;
  }
  .mobile\:text-left,
  .hover\:mobile\:text-left:hover {
    text-align: left;
  }
  .mobile\:text-center,
  .hover\:mobile\:text-center:hover {
    text-align: center;
  }
  .mobile\:text-justify,
  .hover\:mobile\:text-justify:hover {
    text-align: justify;
  }
  .mobile\:text-start,
  .hover\:mobile\:text-start:hover {
    text-align: start;
  }
  .mobile\:text-end,
  .hover\:mobile\:text-end:hover {
    text-align: end;
  }
}
```

# Tablet Text Align

- .tablet:text-right
- .hover:tablet:text-right
- .tablet:text-left
- .hover:tablet:text-left
- .tablet:text-center
- .hover:tablet:text-center
- .tablet:text-justify
- .hover:tablet:text-justify
- .tablet:text-start
- .hover:tablet:text-start
- .tablet:text-end
- .hover:tablet:text-end

```css
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  .tablet\:text-right,
  .hover\:tablet\:text-right:hover {
    text-align: right;
  }
  .tablet\:text-left,
  .hover\:tablet\:text-left:hover {
    text-align: left;
  }
  .tablet\:text-center,
  .hover\:tablet\:text-center:hover {
    text-align: center;
  }
  .tablet\:text-justify,
  .hover\:tablet\:text-justify:hover {
    text-align: justify;
  }
  .tablet\:text-start,
  .hover\:tablet\:text-start:hover {
    text-align: start;
  }
  .tablet\:text-end,
  .hover\:tablet\:text-end:hover {
    text-align: end;
  }
}
```

# Tablet Pc Text Align

- .tablet-pc:text-right
- .hover:tablet-pc\text-right
- .tablet-pc:text-left
- .hover:tablet-pc:text-left
- .tablet-pc:text-center
- .hover:tablet-pc:text-center
- .tablet-pc:text-justify
- .hover:tablet-pc:text-justify
- .tablet-pc:text-start
- .hover:tablet-pc:text-start
- .tablet-pc:text-end
- .hover:tablet-pc:text-end

```css
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  .tablet-pc\:text-right,
  .hover\:tablet-pc\:text-right:hover {
    text-align: right;
  }
  .tablet-pc\:text-left,
  .hover\:tablet-pc\:text-left:hover {
    text-align: left;
  }
  .tablet-pc\:text-center,
  .hover\:tablet-pc\:text-center:hover {
    text-align: center;
  }
  .tablet-pc\:text-justify,
  .hover\:tablet-pc\:text-justify:hover {
    text-align: justify;
  }
  .tablet-pc\:text-start,
  .hover\:tablet-pc\:text-start:hover {
    text-align: start;
  }
  .tablet-pc\:text-end,
  .hover\:tablet-pc\:text-end:hover {
    text-align: end;
  }
}
```

# Pc Text Align

- .pc:text-right
- .hover:pc:text-right
- .pc:text-left
- .hover:pc:text-left
- .pc:text-center
- .hover:pc:text-center
- .pc:text-justify
- .hover:pc:text-justify
- .pc:text-start
- .hover:pc:text-start
- .pc:text-end
- .hover:pc:text-end

```css
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  .pc\:text-right,
  .hover\:pc\:text-right:hover {
    text-align: right;
  }
  .pc\:text-left,
  .hover\:pc\:text-left:hover {
    text-align: left;
  }
  .pc\:text-center,
  .hover\:pc\:text-center:hover {
    text-align: center;
  }
  .pc\:text-justify,
  .hover\:pc\:text-justify:hover {
    text-align: justify;
  }
  .pc\:text-start,
  .hover\:pc\:text-start:hover {
    text-align: start;
  }
  .pc\:text-end,
  .hover\:pc\:text-end:hover {
    text-align: end;
  }
}
```

# Tv Text Align

- .tv:text-right
- .hover:tv:text-right
- .tv:text-left
- .hover:tv:text-left
- .tv:text-center
- .hover:tv:text-center
- .tv:text-justify
- .hover:tv:text-justify
- .tv:text-start
- .hover:tv:text-start
- .tv:text-end
- .hover:tv:text-end

```css
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  .tv\:text-right,
  .hover\:tv\:text-right:hover {
    text-align: right;
  }
  .tv\:text-left,
  .hover\:tv\:text-left:hover {
    text-align: left;
  }
  .tv\:text-center,
  .hover\:tv\:text-center:hover {
    text-align: center;
  }
  .tv\:text-justify,
  .hover\:tv\:text-justify:hover {
    text-align: justify;
  }
  .tv\:text-start,
  .hover\:tv\:text-start:hover {
    text-align: start;
  }
  .tv\:text-end,
  .hover\:tv\:text-end:hover {
    text-align: end;
  }
}
```

# Line Height

The line-height CSS property sets the height of a line box. It's commonly used to set the distance between lines of text. On block-level elements, it specifies the minimum height of line boxes within the element. On non-replaced inline elements, it specifies the height that is used to calculate line box height.

- .line-height-1
- .hover:line-height-1
- .line-height-2
- .hover:line-height-2
- .line-height-3
- .hover:line-height-3
- .line-height-4
- .hover:line-height-4
- .line-height-5
- .hover:line-height-5

```css
.line-height-1,
.hover\:line-height-1:hover {
  line-height: 1rem !important;
}
.line-height-2,
.hover\:line-height-2:hover {
  line-height: 2rem !important;
}
.line-height-3,
.hover\:line-height-3:hover {
  line-height: 3rem !important;
}
.line-height-4,
.hover\:line-height-4:hover {
  line-height: 4rem !important;
}
.line-height-5,
.hover\:line-height-5:hover {
  line-height: 5rem !important;
}
```

# Font Size

The font-size CSS property sets the size of the font. Changing the font size also updates the sizes of the font size-relative length units, such as em, ex, and so forth.

- .font-size-0.5
- .hover:font-size-0.5
- .font-size-0.6
- .hover:font-size-0.6
- .font-size-0.7
- .hover:font-size-0.7
- .font-size-0.8
- .hover:font-size-0.8
- .font-size-0.9
- .hover:font-size-0.9
- .font-size-1
- .hover:font-size-1
- .font-size-1.1
- .hover:font-size-1.1
- .font-size-1.2
- .hover:font-size-1.2
- .font-size-1.3
- .hover:font-size-1.3
- .font-size-1.4
- .hover:font-size-1.4
- .font-size-1.5
- .hover:font-size-1.5
- .font-size-1.6
- .hover:font-size-1.6
- .font-size-1.7
- .hover:font-size-1.7
- .font-size-1.8
- .hover:font-size-1.8
- .font-size-1.9
- .hover:font-size-1.9
- .font-size-2
- .hover:font-size-2
- .font-size-2.5
- .hover:font-size-2.5
- .font-size-3
- .hover:font-size-3
- .font-size-3.5
- .hover:font-size-3.5
- .font-size-4
- .hover:font-size-4
- .font-size-4.5
- .hover:font-size-4.5
- .font-size-5
- .hover:font-size-5
- .font-size-5.5
- .hover:font-size-5.5
- .font-size-6
- .hover:font-size-6
- .font-size-6.5
- .hover:font-size-6.5
- .font-size-7
- .hover:font-size-7
- .font-size-7.5
- .hover:font-size-7.5
- .font-size-8
- .hover:font-size-8
- .font-size-8.5
- .hover:font-size-8.5
- .font-size-9
- .hover:font-size-9
- .font-size-9.5
- .hover:font-size-9.5
- .font-size-10
- .hover:font-size-10

```css
.font-size-0\.5,
.hover\:font-size-0\.5:hover {
  font-size: 0.5rem;
}
.font-size-0\.6,
.hover\:font-size-0\.6:hover {
  font-size: 0.6rem;
}
.font-size-0\.7,
.hover\:font-size-0\.7:hover {
  font-size: 0.7rem;
}
.font-size-0\.8,
.hover\:font-size-0\.8:hover {
  font-size: 0.8rem;
}
.font-size-0\.9,
.hover\:font-size-0\.9:hover {
  font-size: 0.9rem;
}
.font-size-1,
.hover\:font-size-1:hover {
  font-size: 1rem;
}
.font-size-1\.1,
.hover\:font-size-1\.1:hover {
  font-size: 1.1rem;
}
.font-size-1\.2,
.hover\:font-size-1\.2:hover {
  font-size: 1.2rem;
}
.font-size-1\.3,
.hover\:font-size-1\.3:hover {
  font-size: 1.3rem;
}
.font-size-1\.4,
.hover\:font-size-1\.4:hover {
  font-size: 1.4rem;
}
.font-size-1\.5,
.hover\:font-size-1\.5:hover {
  font-size: 1.5rem;
}
.font-size-1\.6,
.hover\:font-size-1\.6:hover {
  font-size: 1.6rem;
}
.font-size-1\.7,
.hover\:font-size-1\.7:hover {
  font-size: 1.7rem;
}
.font-size-1\.8,
.hover\:font-size-1\.8:hover {
  font-size: 1.8rem;
}
.font-size-1\.9,
.hover\:font-size-1\.9:hover {
  font-size: 1.9rem;
}
.font-size-2,
.hover\:font-size-2:hover {
  font-size: 2rem;
}
.font-size-2\.5,
.hover\:font-size-2\.5:hover {
  font-size: 2.5rem;
}
.font-size-3,
.hover\:font-size-3:hover {
  font-size: 3rem;
}
.font-size-3\.5,
.hover\:font-size-3\.5:hover {
  font-size: 3.5rem;
}
.font-size-4,
.hover\:font-size-4:hover {
  font-size: 4rem;
}
.font-size-4\.5,
.hover\:font-size-4\.5:hover {
  font-size: 4.5rem;
}
.font-size-5,
.hover\:font-size-5:hover {
  font-size: 5rem;
}
.font-size-5\.5,
.hover\:font-size-5\.5:hover {
  font-size: 5.5rem;
}
.font-size-6,
.hover\:font-size-6:hover {
  font-size: 6rem;
}
.font-size-6\.5,
.hover\:font-size-6\.5:hover {
  font-size: 6.5rem;
}
.font-size-7,
.hover\:font-size-7:hover {
  font-size: 7rem;
}
.font-size-7\.5,
.hover\:font-size-7\.5:hover {
  font-size: 7.5rem;
}
.font-size-8,
.hover\:font-size-8:hover {
  font-size: 8rem;
}
.font-size-8\.5,
.hover\:font-size-8\.5:hover {
  font-size: 8.5rem;
}
.font-size-9,
.hover\:font-size-9:hover {
  font-size: 9rem;
}
.font-size-9\.5,
.hover\:font-size-9\.5:hover {
  font-size: 9.5rem;
}
.font-size-10,
.hover\:font-size-10:hover {
  font-size: 10rem;
}
```

# Letter Spacing

The letter-spacing CSS property sets the horizontal spacing behavior between text characters. This value is added to the natural spacing between characters while rendering the text. Positive values of letter-spacing causes characters to spread farther apart, while negative values of letter-spacing bring characters closer together.

- .letter-spacing-0.1
- .hover:letter-spacing-0.1
- .letter-spacing-0.2
- .hover:letter-spacing-0.2
- .letter-spacing-0.3
- .hover:letter-spacing-0.3
- .letter-spacing-0.4
- .hover:letter-spacing-0.4
- .letter-spacing-0.5
- .hover:letter-spacing-0.5
- .letter-spacing-0.6
- .hover:letter-spacing-0.6
- .letter-spacing-0.7
- .hover:letter-spacing-0.7
- .letter-spacing-0.8
- .hover:letter-spacing-0.8
- .letter-spacing-0.9
- .hover:letter-spacing-0.9
- .letter-spacing-1
- .hover:letter-spacing-1

```css
.letter-spacing-0\.1,
.hover\:letter-spacing-0\.1:hover {
  letter-spacing: 0.1rem;
}
.letter-spacing-0\.2,
.hover\:letter-spacing-0\.2:hover {
  letter-spacing: 0.2rem;
}
.letter-spacing-0\.3,
.hover\:letter-spacing-0\.3:hover {
  letter-spacing: 0.3rem;
}
.letter-spacing-0\.4,
.hover\:letter-spacing-0\.4:hover {
  letter-spacing: 0.4rem;
}
.letter-spacing-0\.5,
.hover\:letter-spacing-0\.5:hover {
  letter-spacing: 0.5rem;
}
.letter-spacing-0\.6,
.hover\:letter-spacing-0\.6:hover {
  letter-spacing: 0.6rem;
}
.letter-spacing-0\.7,
.hover\:letter-spacing-0\.7:hover {
  letter-spacing: 0.7rem;
}
.letter-spacing-0\.8,
.hover\:letter-spacing-0\.8:hover {
  letter-spacing: 0.8rem;
}
.letter-spacing-0\.9,
.hover\:letter-spacing-0\.9:hover {
  letter-spacing: 0.9rem;
}
.letter-spacing-1,
.hover\:letter-spacing-1:hover {
  letter-spacing: 1rem;
}
```

```css

```

### example

```html
<div class="container">
  <p class="dir-rtl">Hello World !</p>
</div>
```
