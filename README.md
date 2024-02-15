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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/elisilk/huddle-landing-page-with-single-introductory-section](https://github.com/elisilk/huddle-landing-page-with-single-introductory-section)
- Live Site URL: [https://elisilk.github.io/huddle-landing-page-with-single-introductory-section/](https://elisilk.github.io/huddle-landing-page-with-single-introductory-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Flexbox
- Mobile-first workflow

### What I learned

The HTML was fairly simple as it was only one page and with very few components. I did add a wrapper _div_ and a layout-grid _div_ to help with the positioning.

Where I spent most of my time included:

- the background image
- the social icons
- the various margins and paddings
- border radius and box shadows

Although I am not 100% sure of my solution, I spent some time trying to get the Font Awesome social icons to be circular (not oval):

```css
.icon {
  display: inline-block;
  border: 1px solid var(--clr-white);
  border-radius: 50%;
  padding: 0.25em 0.5em;
}
```

### Continued development

I definitely want to learn more about:

- border-radius
- box-shadow

Whoops, I didn't pay enough attention to the one of the key aspects of the challenge, which was to "See hover states for all interactive elements on the page". I definitely have to work on that, and will include the interactive elements of:

- the register button (e.g. [Button Hover Effects](https://www.sliderrevolution.com/resources/css-button-hover-effects/))
- the social icons
- the footer links
- anything else?

And now that I see how Frontend Mentor does a ["design comparison"](https://www.frontendmentor.io/solutions/responsive-landing-page-w-bkgd-image-icons-and-css-custom-properties-ddb86IDU28) with a screenshot of your solution compared to the design, I will spend a little more time getting the spacing so it better aligns with the design.

### Useful resources

- [Responsive layout practice for beginners](https://youtu.be/JFbxl_VmIx0?si=xBqWtxCKLFNJ768b) - This YouTube video by Kevin Powell, in which he talks aloud while solving a different Frontend Mentor challenge, was the model I used to solve this challenge.
- [MDN Web Docs for CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Went here a lot to reference the different CSS properties and the shorthands, and all the great explanations about best practices.

## Author

- Website - [Eli Silk](https://github.com/elisilk)
- Frontend Mentor - [@elisilk](https://www.frontendmentor.io/profile/elisilk)

## Acknowledgments

I definitely want to acknowledge [Kevin Powell](https://www.kevinpowell.co/). Kevin's email newsletter inspired me to give Frontend Mentor a try, and his YouTube video of another Frontend Mentor challenge was the model I used to develop my own solution to this challenge.
