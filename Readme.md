# Tiny Portfolio - Mini Portofolio

This is a forth practice of mine Frontend studies, a personal challenge to improve mine coding skills building own projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Feed Back](#feed-back)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](/src/imagens/screenshot.png)

### Links

- Code URL: [GitHub](https://github.com/Akherox/tiny-portfolio)
- Live Site URL: [GitHub Pages](https://akherox.github.io/tiny-portfolio/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Media query - responsive CSS

### What I learned

How to use audio tag components "autoplay" and "muted".

```html
<audio controls autoplay muted>
  <source src="./Soundtrack.mp3" type="audio/mp3" />
</audio>
```

How to implement an typing text effect.

```css
h2 {
  box-shadow: 0.5em 0 0 #00f7ff;
  width: 22ch;
  overflow: hidden;
  color: #fff;
  white-space: nowrap;
  animation: caret 0.5s step-end infinite alternate, type 5s steps(28, end);
}

@keyframes type {
  0% {
    width: 0;
  }
}
@keyframes caret {
  50% {
    box-shadow: 0.6em 0 0 transparent;
  }
}
```

### Feed Back

I`m going to improve on effects.

### Useful resources

- [Example resource](https://github.com/Akherox/demon-slayer-slider) - This helped me because it is an old project that I did.

## Author

- Linkedin - [Bryan Bravo](https://www.linkedin.com/in/alex-bravo-008-mk)
- GitHub Profile - [@Akherox](https://github.com/Akherox)
