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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](/design/desktop-design.jpg)


### Links

- Live Site URL: [ffernandocosta.github.io/huddle](https://ffernandocosta.github.io/huddle/)

## My process

I started with mobile first design and focused on getting my CSS variables and utility classes ready. After that I build my whole html content all at once so I can style with CSS later.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS variables
- CSS utility classes
- Mobile-first workflow


### What I learned

Learned how to use CSS variables and utility classes, makes it easier to style the HTML content later and to also repair or change anything later in the project.

```html
<h1>Some HTML code I'm proud of</h1>
          <div class="container">
          <img src="images/illustration-mockups.svg">
          
          <div class="heading-container">
            <h1 class="fw-semi-bold ff-heading fs-primary-heading color-primary-white | container-h1">Build The Community Your Fans Will Love</h1>
            <p class="ff-body fs-body fw-regular color-primary-white | container-p">Huddle re-imagines the way we build communities. You have a voice, but so does your audience. Create connections with your users as you engage in genuine discussion.</p>
            <button class="button fs-body fw-regular ff-heading color-primary-white">Register</button>
          </div>

        </div>
```
```css
@import url(icons.css);

:root {
    --clr-violet: hsl(257, 40%, 49%);
    --clr-soft-magenta: hsl(300, 69%, 71%);
    --clr-primary-white: hsl(0, 0%, 100%);
    --ff-headings: 'Poppins', sans-serif;
    --ff-body: 'Open Sans', sans-serif;;
    --fw-regular: 400;
    --fw-semi-bold: 600;
    --fs-primary-heading: 26px;
    --fs-body: 16px;
    --fs-desktop-heading: 45px;
    --fs-desktop-body: 20px;
}

/* UTILITY CLASSES */

.fs-primary-heading { font-size: var(--fs-primary-heading); line-height: 1.5; }

.fs-body { font-size: var(--fs-body);}

.fw-regular { font-weight: var(--fw-regular); }

.fw-semi-bold { font-weight: var(--fw-semi-bold);}

.ff-heading { font-family: var(--ff-headings);}

.ff-body { font-family: var(--ff-body);}

.bg-primary { background-color: var(--clr-violet);}

.color-primary-white { color: var(--clr-primary-white);}
```


### Continued development

On my future projects I want to tackle more complex designs with forms, lists, css grid and flex box to challenge myself and become a better developer.


### Useful resources

- [Font Awesome](https://fontawesome.com/) - This library helped me with social icons for this project.

## Author

- Website - [Fernando Costa](https://github.com/ffernandocosta)
