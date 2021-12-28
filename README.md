
# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Live Site URL: [nft-preview-card](https://nicosq77.github.io/NFT-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
### What I learned


```html
<span>Some HTML code I'm proud of</span>

<div class="img-containter">
  <img class="img-equilibrium">
  <div class="overlay">
    <img class="view">
  </div>

</div>
```
```css
span{
  display: flex;
}

.overlay{
  position: absolute;
  opacity:0;
  background-color: hsl(178, 100%, 50%);
}

.img-equilibrium:hover .overlay{
  opacity:0.5;
}

```
