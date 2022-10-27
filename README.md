# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop Site](Screenshot_Desktop.jpg)
![Mobile Site](Screenshot_Mobile.jpg)

### Links

- Solution URL: [https://github.com/Mzu-Soci/Product-preview-card-component.git](https://your-solution-url.com)
- Live Site URL: [https://mzu-soci.github.io/Product-preview-card-component/](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

-Switching images using CSS based on the media query settings.
-Using flex box

To see how you can add code snippets, see below:

```css
@media only screen and (min-width: 850px) {
  .image {
    height: 540px;
    background-image: url(../images/image-product-desktop.jpg);
    background-size: cover;
    border-radius: 10px 0 0 10px;
    flex: 1;
  }
}

@media only screen and (max-width: 850px) {
  .image {
    height: 241px;
    background-image: url(../images/image-product-mobile.jpg);
    background-size: cover;
    border-radius: 10px 10px 0 0;
  }
}
```

### Continued development

-I would like to learn how to center a div on a page, the div must be centered verticaly,
-Need to learn more about using flex to position elements

### Useful resources

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

I learned how to use html and css on Angela Yu's Udemy Course: Web developer Bootcamp
