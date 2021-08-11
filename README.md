# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). ![Design preview for the Profile card component coding challenge](./design/desktop-preview.jpg).Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

[Desktop version](./design/desktop-design.jpg)
[Mobile version](./design/mobile-design.jpg)

### Links

- [Solution URL](https://tmraz.github.io/Social_proof_section_solution.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](./css/main.css) - For desktop style
- [Styled Components](./css/mmobile.css) - For mobile style

### What I learned

Snippets, see below:

```css
/* === layout grid === */
    display: grid;
    grid-template-columns: [col] 15rem [col] 15rem [col] auto [col] auto [col] auto;
    grid-template-rows: [row] 50% [row] auto;

header {
    grid-column: col / span 2;
    grid-row: row 1;
}
```

### Useful resources

- [Grid system URL]https://gridbyexample.com/examples/example8/)

- [Flexbox URL](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
