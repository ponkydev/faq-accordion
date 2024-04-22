# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview
This is a good challange if you want to work on transition and Javascript.

### The challenge

Users should be able to:

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./faq-screenshot.jpeg)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

```js
faq.addEventListener("click", () => {
          if (answer.classList.contains("visible")) {
            // If FAQ is already opened
            answer.classList.toggle("visible");
            answer.classList.add("fade-out");
            open.classList.remove("invisible");
            close.classList.add("invisible");
          } else {
            // If FAQ is not opened yet
            answer.classList.toggle("visible");
            answer.classList.remove("fade-out");
            open.classList.add("invisible");
            close.classList.remove("invisible");
          }
        })
```

## Author

- Website - [Angel Henriquez](https://github.com/ponkydev)
- Frontend Mentor - [@pr0g4ng3l](https://www.frontendmentor.io/profile/pr0g4ng3l)
- Twitter - [@navimmii](https://twitter.com/navimmii)
- Linkedin - [Angel Ivan Henriquez Martinez](https://www.linkedin.com/in/angel-ivan-henr%C3%ADquez-mart%C3%ADnez-16a6b6218/)
