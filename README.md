# Social-media-manager

# Frontend Mentor - Bento grid solution

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview
This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). The aim of this challenge was to build a responsive page using css grid.

### The Challenge

####•Live Site: https://cma1uba.github.io/Social-media-manager/

####•Solution: https://github.com/cma1uba/Social-media-manager

### Built with

- HTML5
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- How to structure UI with CSS flexbox and Grid
- How to to position child elements in Grid
- How to set up HTML5 mockup for grid manipulation

```html
<div class="container">
  <div class="child1"></div>
  <div class="child2"></div>
</div>
```
To display grid:
```css
.container {
  display: grid;
  grid-column-template: repeat(4, 1fr)
}
/*specifying grid elements position*/
.child1{
 grid-row: 1/3;
 grid-column: 2/4;
}
```

### Continued development

• Optimize my css to reduce repeatition
• improve responsiveness across devices

### Useful resources

- [Example resource 1](https://www.w3schools.com) - Was very helpful in understanding Position elements in grid.

## Author
   • Maluba Choonya.
