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

- Hide/Show the answer to a question when the question is clicked.
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Screenshot%20web.png)
![](./Screenshot%20mob.png)


### Links

- Solution URL: [](https://your-solution-url.com)
- Live Site URL: [](https://your-live-site-url.com)

## My process

### Built with

- HTML5 form
- CSS custom properties
- Pseudo elements (after - before)
- web-first workflow

### What I learned

- I learned how to make the answer switch between show and hide with just css and it's pseudo elements, with no JavaScript as I still didn't learned it yet.

- Ive been more confort with Responsive Layouts.

```html
<label for="faq1"><h2>What is Frontend Mentor, and how will it help me?</h2></label>
```
```css
label::before {
  content: url(assets/images/icon-plus.svg);
}
p {
   display: none;
   opacity: 0;
}
input:checked ~ p {
  display: block;
  opacity: 1;
}
```


### Continued development

- Yet I'm looking forward to add more JS to my codes specially in that part of togelling between hide and show the answer by clicking on the same input's label.

- The accessability part of moving between checkboxes by just the keyboard, I couldn't figure it out yet.

### Useful resources

- [Bootstrap Website](https:///getbootstrap.com/) - That website helping me a lot through my road; In this project, I used it to give me the perfect screen sizes (Breakpoints) so I can make a neat responsive layout with right dimentions.
- [ChatGPT](https://chatgpt.com/) - Some times there's a specific code I spend so many time to debug it, and I just need a second brain to give a tip, and for that I use ChatGPT from time to time and adapt his ideas to my code line.

## Author

- Frontend Mentor - [@H-Keshk](https://www.frontendmentor.io/profile/H-Keshk)
- X - [@HudaKeshk15889](https://www.twitter.com/HudaKeshk15889)
- Facebook - [@HudaKeshk](https://www.facebook.com/HudaKeshk)
- Github - [@H-Keshk](https://github.com/H-Keshk)
- LinkedIn - [@hoda-mohamed](https://www.linkedin.com/in/hoda-mohamed-180735107/)


