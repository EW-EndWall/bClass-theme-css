# Default Settings

```css
* {
  outline: 0;
  padding: 0;
  margin: 0;
}
:root {
  font-size: 0.9rem;
}
body {
  margin: 0;
  padding: 0;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  color: var(--contentTextPrimary);
}
p {
  color: var(--contentTextSecondary);
}
a {
  color: var(--contentTextPrimary);
  transition: all 0.5s ease;
}
a:hover {
  transform: scale(1.2);
  opacity: 0.7;
}
@font-face {
  font-family: "itimregular";
  src: url("fonts/itim-regular-webfont.woff2") format("woff2"), url("fonts/itim-regular-webfont.woff")
      format("woff");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}
body {
  font-family: "itimregular", Arial, sans-serif;
}
body:not(.xfont) {
  font-family: Arial, sans-serif;
}
```

### screen size

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  :root {
    font-size: 0.8rem;
  }
}
/* tablet < 768px */
@media screen and (min-width: 480px) and (max-width: 768px) {
  :root {
    font-size: 0.7rem;
  }
}
/* tablet-pc < 992 */
@media screen and (min-width: 768px) and (max-width: 992px) {
  :root {
    font-size: 0.8rem;
  }
}
/* pc < 1200 */
@media screen and (min-width: 992px) and (max-width: 1200px) {
  :root {
    font-size: 0.9rem;
  }
}
/* tv > 1200 */
@media screen and (min-width: 1200px) {
  :root {
    font-size: 1rem;
  }
}
```
