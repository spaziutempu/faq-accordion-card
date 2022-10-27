# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [GitHub](https://github.com/spaziutempu/faq-accordion-card)
- Live Site URL: [https://darling-medovik-8f6dca.netlify.app/](https://darling-medovik-8f6dca.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- css combinators
- Flexbox
- checkbox accordion trick

### What I learned

##### - with this challenge i learned how to use the checkbox/radio trick to display/hide some text without using javascript,

```css
.accordion_input:checked ~ .accordion_label .accordion_text {
  display: block;
}
```

- a little bit more about position: absolute

- by the way i got lot of difficulty with logos display, still not finishing to place them correctly yet, it was quite frustrating to don't find the proper way to do it.

### Continued development

- Need to Fix logos display

### Useful resources

- [How to create a CSS-Only Accordion from dcode](https://www.youtube.com/watch?v=pzy_QStQaqA) - This helped me to basic understanding checkbox accordion.

## Author

- Website - [Github](https://github.com/spaziutempu)
- Frontend Mentor - [@spaziutempu](https://www.frontendmentor.io/profile/spaziutempu)
