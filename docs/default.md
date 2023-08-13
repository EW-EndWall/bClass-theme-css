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
  color: var(--contentTextSecondary);
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

mobile < 480px
<br>
font-size: 0.8rem;
<br>
tablet < 768px
<br>
font-size: 0.7rem;
<br>
tablet-pc < 992
<br>
font-size: 0.8rem;
<br>
pc < 1200
<br>
font-size: 0.9rem;
<br>
tv > 1200
<br>
font-size: 1rem;
