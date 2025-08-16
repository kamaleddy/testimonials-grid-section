# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot/Desktop%20View.png)
![](./screenshot/Mobile%20View.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [My live site](https://kamaleddy.github.io/testimonials-grid-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this project I learned how to build responsive website using grid with `grid-template-columns`, `repeat()`, and media queries.

```css
.main {
  width: min(85%, 1152px);
  margin: 10vh auto;
  display: grid;
  gap: 2em;
}

@media (min-width: 75rem) {
  .main {
    grid-template-columns: repeat(4, 1fr);
  }

  .bg-color-one {
    grid-column: 1 / span 2;
  }

  .bg-color-four {
    grid-column: 2 / span 2;
  }

  .bg-color-five {
    grid-column: 4;
    grid-row: 1 / span 2;
  }
}
```

### Continued development

To enhance user experience and make your testimonials grid more engaging, I should explore CSS animations and transitions and apply to this project and make smoothly animate property changes.

### Useful resources

- [Grid](https://web.dev/learn/css/grid) - Helped me in understanding basic about grid.
- [An Interactive Guide to CSS Grid](https://web.dev/learn/css/grid) - This is an amazing article which helped me finally understand grid with more advanced and i can visualize how the grid work in 2d. I'd recommend it to anyone still learning this concept.

## Author

- Github - [@kamaleddy](https://github.com/kamaleddy)
- Frontend Mentor - [@kamaleddy](https://www.frontendmentor.io/profile/kamaleddy)
