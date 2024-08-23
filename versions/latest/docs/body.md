# Body Color Pallete

- .dark
- .light
- .black
- .transparent

### example

```html
<body class="light">
  <div class="container">
    <p>Hello World !</p>
  </div>
</body>
```

### code

````css
/* * color default and dark */
body,
body.dark {
  --headerBg: #252525;
  --footerBg: #252525;
  --headerText: #90949c;
  --footerText: #90949c;
  --contentBg: #191919;
  --contentBgPrimary: #424242;
  --contentBgSecondary: #303030;
  --contentTextPrimary: #90949c;
  --contentTextSecondary: #f5f5f5;
  --plainBg: #101010;
}
/* * color light */
body.light {
  --headerBg: #90949c;
  --footerBg: #90949c;
  --headerText: #5c5c5c;
  --footerText: #5c5c5c;
  --contentBg: #81858c;
  --contentBgPrimary: #bdbdbd;
  --contentBgSecondary: #e0e0e0;
  --contentTextPrimary: #5c5c5c;
  --contentTextSecondary: #424242;
  --plainBg: #cfd8dc;
}
/* * color black */
body.black {
  --headerBg: #000000;
  --footerBg: #000000;
  --headerText: #818181;
  --footerText: #818181;
  --contentBg: #000000;
  --contentBgPrimary: #505050;
  --contentBgSecondary: #111111;
  --contentTextPrimary: #818181;
  --contentTextSecondary: #f5f5f5;
  --plainBg: #101010;
}
/* * color transparent */
body.transparent {
  --headerBg: transparent;
  --footerBg: transparent;
  --headerText: #000000;
  --footerText: #000000;
  --contentBg: transparent;
  --contentBgPrimary: transparent;
  --contentBgSecondary: transparent;
  --contentTextPrimary: #000000;
  --contentTextSecondary: #424242;
  --plainBg: url("https://www.w3schools.com/css/paris.jpg");
}
body {
  background: var(--plainBg);
  color: var(--contentTextPrimary);
}
```
````
