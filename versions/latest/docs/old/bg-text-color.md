# Background color

- .bg-transparent
- .hover:bg-transparent
- .content-1-bg
- .hover:content-1-bg
- .content-2-bg
- .hover:content-2-bg
- .content-3-bg
- .hover:content-3-bg

# Text color

- .text-transparent
- .hover:text-transparent
- .content-1-text
- .hover:content-1-text
- .content-2-text
- .hover:content-2-text

### example

```html
<div class="container">
  <div class="content-1-bg content-1-text">
    <div class="bg-transparent hover:text-transparent">
      <p>Hello World !</p>
    </div>
  </div>
</div>
```

```css
.content-1,
.content-1-bg,
.hover\:content-1-bg:hover {
  background-color: var(--contentBg);
}
.content-2,
.content-2-bg,
.hover\:content-2-bg:hover {
  background-color: var(--contentBgPrimary);
}
.content-3,
.content-3-bg,
.hover\:content-3-bg:hover {
  background-color: var(--contentBgSecondary);
}
```
