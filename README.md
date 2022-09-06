# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size

### Screenshot

![](assets/img/screenshot.png)

### Links

- Solution URL: [Click here](https://github.com/24FContreras/FM-statsPreviewCardComponent)
- Live Site URL: [Click here](https://24FContreras.github.io/FM-statsPreviewCardComponent)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Sass (scss)
- Flexbox
- Mobile-first workflow

### What I learned

This challenge presented me with one major issue: controlling the image's behaviour and filter.

For the image styling, I used a backdrop a purple background. Then i used mix-blend-mode property and opacity to match the image's appearance to the reference.

To make the image's behaviour better with width shifts, In the media query I gave it height: 100% and object-fit: cover.

```scss
img {
  width: 100%;
  mix-blend-mode: multiply;
  opacity: 0.75;
}
```

```scss
// INSIDE MEDIA QUERY
img {
  height: 100%;
  object-fit: cover;
}
```

### Continued development

This is the last challenge with card-like layout in the newbie category. From now, I'll move to page payouts!

### Useful resources

- [W3 Schools CSS mix-blend-mode Property](https://www.w3schools.com/cssref/pr_mix-blend-mode.asp) - Reference for all values of mix-blend-mode.

## Author

- Frontend Mentor - [@24FContreras](https://www.frontendmentor.io/profile/24FContreras)
- Github - [@24FContreras](https://github.com/24FContreras)
