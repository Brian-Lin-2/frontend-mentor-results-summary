# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview
Created a basic results summary page that displays an overall score as well as scores for specific areas.

### The challenge
Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

Desktop Version:
<br/> <img width="700" alt="image" src="https://user-images.githubusercontent.com/19761406/228931970-8860f88e-2184-464a-8356-8e7bc4d7e43e.png">

Desktop Version (Active State):
<br/> <img width="700" alt="image" src="https://user-images.githubusercontent.com/19761406/228928108-031fbfb9-548b-4cbb-8795-4234241cb679.png">

Mobile Version:
<br/> <img width="193" alt="image" src="https://user-images.githubusercontent.com/19761406/228928790-25fbf73f-e351-4b04-9507-1d9a28c7fcfc.png">

### Links

- Solution URL: https://github.com/Brian-Lin-2/frontend-mentor-results-summary
- Live Site URL: https://frontend-mentor-results-summary-rho.vercel.app

### Built with

- HTML5
- CSS
- Flexbox
- Mobile-first workflow

### What I learned

I learned how to use gradients to style my css.

```css
    /* Gradient is a special type of background image. */
    /* color1, transition percentage (default 50%), color2 */
    background: linear-gradient(hsl(252, 100%, 67%), 25%, hsl(241, 81%, 54%));
```

I learned more about media queries and how they affect the layout of a website.

```css
/* Desktop Version. */
@media screen and (min-width: 500px) {
    .body {
        display: flex;

        justify-content: center;
        align-items: center;
    }

    .container {
        width: 1440px;
        height: 1080px;
    }
}
```

### Continued development
Moving forward, I would like more practice with media queries and css styling in general.

## Author
- Frontend Mentor - [@Brian-Lin-2](https://www.frontendmentor.io/profile/Brian-Lin-2)
