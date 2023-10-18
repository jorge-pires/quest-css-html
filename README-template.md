# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Design preview for the Huddle landing page with single introductory section](./design/desktop-design.jpg)

### Links

- Solution URL: https://github.com/jorge-pires/quest-css-html.git
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The most important tip I can give you is regarding the responsive background, without a defined height-min you can't make it responsive, you can use the code below:

```css
.bg {
    background: url(../images/bg-desktop.svg) center left no-repeat;
    background-size: auto 100%;
    padding: 55px 70px 0px 70px;
    min-height: 100vh;
}
```
## Author

- Frontend Mentor - [jorge-pires](https://github.com/jorge-pires)

## Acknowledgments

I would first like to thank God for giving me the wisdom to carry out this project, and I would also like to thank the creators of the DevQuest course and their team. It was through the knowledge I acquired on the course that I was able to carry out this project.