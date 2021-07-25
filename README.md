# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Links

- Solution URL: [FAQ-accordion-card.git](https://github.com/Charlie025x/FAQ-accordion-card.git)
- Live Site URL: [faq-accordion-card](https://charlie025x.github.io/FAQ-accordion-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Flexbox has kept my card's child divs evenly spaced in my past projects, however not on this one due to the images affecting the divs porportions, in the desktop view. I was able to keep my card even with 

```css
.faq-container, .image-container {
  flex: 1; /*splits card in half */
}
```

### Continued development

Image positioning is still a work in progress. I'm currently posistioning my images with something like
```css
.img {
  position: relative ;
  right: 10px;
  bottom: 10px;
}
```
 But my images move around as I resize my window. Will further look into improving.

 My background gradient doesn't extend with my page's growth due to using the accordion. Leaving a purple bar in the bottom of the page.

### Useful resources

- [Left Half and Right Half Layout – Many Different Ways](https://css-tricks.com/left-and-right/) - I referenced this page to evenly divide my flexbox card in desktop view.

- [How TO - Collapsibles/Accordion](https://www.w3schools.com/howto/howto_js_accordion.asp) - I stole some javascript code from w3schools to get my accordion working

## Author

- Website - [Charlie Alonso](https://github.com/Charlie025x)
- Frontend Mentor - [@Charlie025x](https://www.frontendmentor.io/profile/Charlie025x)