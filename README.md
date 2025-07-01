# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Frontend Mentor FAQ Accordion Solution](https://www.frontendmentor.io/solutions/responsive-faq-accordion-using-mobile-first-approach-KwLHDEaQKO)
- Live Site URL: [FAQ Accordion](https://jezzydev.github.io/faq-accordion/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- JavaScript

### What I learned

One technique to hide/unhide an element is to manipulate its maxHeight and overflow properties:

```css
.answer-container {
  margin-top: 24px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.3s ease-in-out;
}
```

```js
panel.style.maxHeight = panel.style.maxHeight
  ? null
  : panel.scrollHeight + "px";
```

### Continued development

Master JavaScript Fundamentals by continuing to work on more challenges.

### Useful resources

JavaScript fundamentals and refresher

- [The Modern JavaScript Tutorial](https://javascript.info/)
- [Eloquent JavaScript](https://eloquentjavascript.net/)

Quick search, glossary

- [MDN](https://developer.mozilla.org/en-US/docs/Web)

## Author

- Website - [jezzydev](https://github.com/jezzydev)
- Frontend Mentor - [@jezzydev](https://www.frontendmentor.io/profile/jezzydev)
