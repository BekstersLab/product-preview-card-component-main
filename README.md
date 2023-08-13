# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [My Solution](https://beksterslab.github.io/product-preview-card-component-main)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### Continued development

Further revision/work is required on flexbox. I struggled to get before:: and after:: pseudo-elements to work to add a margin/padding between certain elements (sale/full price and the cart icon/button text). Googling came up with the solution to apply display:block to the parent element. I tried adding this to all classes for container elements all the way up to, but not including, main but this made no difference.
Fix: I added multiple non-breaking spaces where needed which I am not happy about. I'd love to know where I've gone wrong?
I did manage to get the pseudo-elements to work with adding content eg.

```css
.sale-price::after {
  content: "Will this work";
}
```

This added text between the sale and full price. I am not sure why padding and margin won't work.

## Author

- Frontend Mentor - [@BekstersLab](https://www.frontendmentor.io/profile/BekstersLab)
