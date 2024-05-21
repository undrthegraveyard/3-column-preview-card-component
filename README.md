
## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

A responsive 3-column card component.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./design/Final%20Design%20Desktop%20Preview.png)
![](./design/Final%20Design%20Mobile%20Preview.png)
![](./design/Final%20Design%20Tablet%20Preview.png)

### Links

- Solution URL:(https://github.com/undrthegraveyard/3-column-preview-card-component.git)
- Live Site URL:(https://undrthegraveyard.github.io/3-column-preview-card-component/)

## My process

- Mobile first design and then scaled it up to larger screen sizes using @media queries. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I used selectors to select specific div elements with the same class in the article element.

```css
article div:first-of-type{
    background-color: var(--clr-primary1-400);
    border-radius: 0.5rem 0.5rem 0 0;
    .cars__primary-button{
        color: var(--clr-primary1-400);
    }
    .cars__primary-button:hover,
    .cars__primary-button:focus
    {
    background-color: var(--clr-primary1-400);
    color: var(--clr-accent-300);
    }
}
```
## Author

-- Website - [Shivam Agarwal](https://www.shivamagarwal.au)
- Frontend Mentor - [@undrthegraveyard](https://www.frontendmentor.io/profile undrthegraveyard)
- Twitter - [@shivam_agarwaal](https://twitter.com/shivam_agarwaal)
