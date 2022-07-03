# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.jpeg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Fluid typescale and spacing, Andy Bell's CUBE CSS methodology

```html
<section class="card__content stack-s">
  <div class="card__copy stack-2xs">
    <h1>Order Summary</h1>
    <p>
      You can now listen to millions of songs, audiobooks, and podcasts on any
      device anywhere you like!
    </p>
  </div>
  ...
</section>
```

```css
.stack-2xs > * + * {
  margin-top: var(--space-2xs-xs);
}
.stack-s > * + * {
  margin-top: var(--space-s-m);
}
```

### Useful resources

- [CUBE CSS](https://cube.fyi/) - This helped me to write less and composable CSS.
- [A Modern CSS Reset](https://piccalil.li/blog/a-modern-css-reset/) - This is an amazing article which helped to reset my CSS before I began to write any more styles.

## Author

- Frontend Mentor - [@Adej0la](https://www.frontendmentor.io/profile/Adej0la)
- Twitter - [@\_adejola](https://www.twitter.com/_adejola)
