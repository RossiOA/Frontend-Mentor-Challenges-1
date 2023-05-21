# Frontend Mentor - NFT preview card component project

This is an end project of the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).

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

## Overview

### The challenge

I had to create a preview card for an NFT based on the designs given by Frontend Mentor.

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I had to investigate a little bit because I could not hover the image to the active state. I learned how to do it from scratch. [Code below]

```css
.container .image {
    position: relative;
}
.container .image div {
    position: absolute;
    top: 0;
    background-color: hsl(178, 100%, 50%, 50%);
    width: 100%;
    height: calc(100% - 5px);
    z-index: 999;
    opacity: 0;
    transition: opacity .2s ease-in-out;
    border-radius: 1rem;
}
.container .image div:hover {
    cursor: pointer;
    opacity: .5;
}
.container .image div img {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
.container .image img {
    border-radius: 1rem;
}
```
## Author

- Website - [Rocio Schkair]
- Frontend Mentor - [@RossiOA](https://www.frontendmentor.io/profile/RossiOA)
- Twitter - [@sweetie_freaky](https://www.twitter.com/sweetie_freaky)
# Frontend-Mentor-Challenges-1
