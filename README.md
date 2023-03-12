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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot-mobile.png)
![](./screenshot-desktop.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In this ptoject I learned about the background-size property to adjust the background image, Here I have given the different backround size for different screen. see below code.

```html
 <div class="huddle">
            
      <div class="upper">
        <div class="huddle__logo">
          <img src="./images/logo.svg" alt="Huddle Logo">
        </div>
  
        <div class="huddle__mockups">
          <img src="./images/illustration-mockups.svg" alt="Huddle illustration mockups">
        </div>
      </div>
```
```css

.huddle{
    display: flex;
    flex-direction: column;
    max-width: 23.4rem;
    background-color: var(--clr-violet);
    background-image: url(./images/bg-mobile.svg); 
    background-repeat: no-repeat;
    background-size: 100% 52%;
}


@media (min-width: 600px) {
    .huddle{
        flex-direction: row;
        min-width: 75.5rem;
        background-image: url(./images/bg-desktop.svg);
        background-repeat: no-repeat;
        background-size: 85% 100%;
        margin-top: 5rem;
    }
}
```


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

