# Default Scrollbar

```css
::-webkit-scrollbar {
  width: 0.5rem;
}
::-webkit-scrollbar-thumb {
  background-color: var(--contentTextPrimary);
}
::-webkit-scrollbar-thumb:hover {
  background-color: var(--contentBgPrimary);
}
::-webkit-scrollbar-track {
  background-color: var(--contentTextSecondary);
  box-shadow: inset 0 0 0.3rem var(--contentTextPrimary);
}
::-webkit-scrollbar-track-piece {
  background-color: transparent;
}
```

# Default html element css

```css
* {
  outline: 0;
}
:root {
  font-size: 0.9rem;
  --transparent: transparent;
}
body {
  margin: 0;
  padding: 0;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
}
a {
  cursor: pointer;
  color: inherit;
  transition: all 0.5s ease;
  text-decoration: none;
}
a:hover {
  color: var(--contentTextSecondary);
}
video::cue {
  background-color: rgba(0, 0, 0, 0.5);
  font-size: 1rem;
}
```

```css
/* mobile < 480px */
@media screen and (max-width: 480px) {
  :root {
    font-size: 0.8rem;
  }
}
```
