# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](screenshot.png)

### Links

- Solution URL: [Solution](https://github.com/JustANipple/fylo-data-storage-component-master)
- Live Site URL: [Live site](https://justanipple.github.io/fylo-data-storage-component-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Josh's Custom CSS Reset

### What I learned

Images should be always in a container (div) to mantain their aspect ratio. This is the method i used for document, folder and upload icons. Otherwise they look worse
Background image can be resized to get positioned at half page
To make triangles, it is necessary to play with borders while having width and height at 0.

This is how i made the triangle for the "185 GB LEFT"

```css
.triangle {
    width: 0;
    height: 0;
    border-top: 30px solid transparent;
    border-bottom: 30px solid transparent;
    border-right: 30px solid white;
    position: absolute;
    right: 0;
    top: 50%;
  }
```

### Continued development

Changing box positioning and shifting it half outside from the container has been a challenge and i don't think i made it the right way. I'll organize HTML better next time for better responsiveness
The white circle in the colored bar is not right but i didn't find a better way to have it positioned with the right spacings

### Useful resources

- [Triangle shape](https://css-tricks.com/snippets/css/css-triangle/) - This helped to make the "185 GB LEFT" tail
- [Positioning](https://developer.mozilla.org/en-US/docs/Web/CSS/position) - This helped to shift blocks outside of the container

## Author

- Frontend Mentor - [@JustANipple](https://www.frontendmentor.io/profile/JustANipple)
