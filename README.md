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

![Desktop-photo](solutions/desk-main.png)
![Mobile-photo](solutions/mobile-main.png)

### Links

- Solution URL: (https://github.com/hassanmoaa/stats-preview-card-FrontEndMentor.git)
- Live Site URL: (https://eclectic-youtiao-e0c3ae.netlify.app)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Google Fonts
- Media Queries

### What I learned

I learned how to use media queries effectively in order to make a website responsive. This allowed me to create the mobile design correctly.

I learned how to use mix-blend-mode in css in order to do the color-overlay.

```
.blend {
    width: 50%;
    background-color: var(--accent);
}

.blend-1 {
    display: none;
}

.img-1 {
    display: block;
    width: 100%;
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px;
    background-size: cover;

    mix-blend-mode: multiply;
    opacity: 0.8;
}

.img-2 {
    display: block;
    width: 100%;

    mix-blend-mode: multiply;
    opacity: 0.8;

    display: none;
}

```

### Continued development

- I want to learn more about css by creating multi-page websites

### Useful resources

- ![FEM-Discord-Server] - I asked for help in the help forum and got a lot of useful advice from members of the discord server especially the admins and mods are so cooperative.

- (https://www.w3schools.com) - W3S helped me getting some help!

## Author

- Frontend Mentor - [@hassanmoaa](https://www.frontendmentor.io/profile/hassanmoaa)
