# Frontend Mentor - Product Preview Card Solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Overview

### The Challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Live Site URL: (https://productcardsolutionfrontendmentor.netlify.app/)

## My Process

### Built with

- Semantic HTML5 markup
- SCSS
- Flexbox
- Mobile-first workflow
- BEM methodology

### What I Learned

This project was particularly useful for improving my SCSS skills, especially in working with mixins. I gained practical experience in:

- Creating reusable breakpoint mixins for responsive design

```scss
@mixin mobile {
  @media screen and (max-width: 480px) {
    @content;
  }
}
```

- Writing flexible typography mixins

```scss
@mixin typography($font, $size, $weight, $color) {
  font-family: $font;
  font-size: $size;
  font-weight: $weight;
  color: $color;
}
```

- Implementing flexbox mixins for better layout control

```scss
@mixin flex($direction, $justify, $align) {
  display: flex;
  flex-direction: $direction;
  justify-content: $justify;
  align-items: $align;
}
```

The project helped me understand how to write more maintainable and reusable SCSS code using mixins, making the styling process more efficient and organized.
