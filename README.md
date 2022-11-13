# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshots

![](./3-component/Screenshots/Mobile%20Design.jpeg)
![](./3-component/Screenshots/Desktop%20Design.jpeg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SCSS

### What I learned

This was an awesome project to refine my flexbox skills as I felt more comfortable using it. I also improved my media query knowledge, I used it to transition easily into desktop without a lot if issues. Here is how I did it :


```css
@media (max-width: 89.9375em) {
  .mobile {
    padding: 30px 0 30px 0;
  }
}

@media (min-width: 90em) {
  .desktop {
    display: flex;
    height: 100vh;
    flex-direction: row;
    justify-content: center;
    align-items: center;
  }
  .desktop__border-radius-sedan {
    border-radius: 10px 0 0 10px;
  }
  .desktop__border-radius-luxury {
    border-radius: 0 10px 10px 0;
  }
}

```


### Continued development

As this point I will be using flexbox a lot more as I feel more familiar with it as well as mobile first design as it made me understand media queries a lot better.


## Author


- Frontend Mentor - [@TK-LS97](hhttps://www.frontendmentor.io/profile/TK-LS97)
