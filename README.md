# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

Design a Product preview card component

### The challenge

The challenge is to build out this product preview card component and get it looking as close to the design provided by Frontend Mentor as possible.

Users would be able to:

- View the optimal layout depending on their device's screen size i.e. responsive
- See hover and focus states for interactive elements

### Screenshot

![](./screenshots/desktop%20ss.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I started building the card, not by coding, but carefully breaking down the designs given so as to be able too get a good html markup for the layout. I designed mobile first so as not to worry about the mobile responsiveness, as i found it easier to make bigger screen sizes responsive.

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I was able to reinforce my flebox layout knowledge by using it on this project. Most important thing, was using the <Piture> tag for the first time. I needed it to change the mobile img to desktop image upon screen resize. Using the srcset, source, size attributes I was able to acheive this. I found a simpler way to do this same functionality, but it was a good learning and reaserch experience.

```html
<picture>
  <source
    media="(max-width:499px)"
    srcset="./images/image-product-mobile.jpg"
  />
  <source
    media="(min-width: 500px)"
    srcset="./images/image-product-desktop.jpg"
  />
  <img
    src="./images/image-product-mobile.jpg"
    alt="Bottle of perfume"
    class="img"
  />
</picture>
```

### Continued development

I would like to use JS to change the images upon screen resize, so definitely will still work on that

## Author

- GitHub - [Funsho Ayobanjo](https://github.com/ayobanjo)
- Frontend Mentor - [@ayobanjo](https://www.frontendmentor.io/profile/ayobanjo)
- Twitter - [@AyobanjoFunsho](https://www.twitter.com/ayobanjofunsho)

## Acknowledgments

My acknowledgments goes to FrontEnd mentor for the platform provided to hone my skills
