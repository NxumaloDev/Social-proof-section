# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![Screenshot](<images/Screenshot 2023-08-14 190225.png>)

![Screenshot](<images/Screenshot 2023-08-14 190254.png>)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The picture tag is of those HTML i have recently discorvered and they are a game changer. Avoids usage of JavaScript with regards to changing image based on the screen width and reinforces my semantic HTML skills.

```html
 <picture>
  <source media="(min-width:650px)" srcset="img_pink_flowers.jpg">
  <source media="(min-width:465px)" srcset="img_white_flower.jpg">
  <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
</picture> 
```

### Useful resources

- [W3schools](https://www.w3schools.com/)

## Author

- Frontend Mentor - [@NxumaloDev](https://www.frontendmentor.io/profile/NxumaloDev)
- Instagram - [@sarcasm_emoji](https://www.instagram.com/sarcasm_emoji)

## Acknowledgments

- FrontEnd Mentor
- W3schools
