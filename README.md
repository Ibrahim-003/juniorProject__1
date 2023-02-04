# Frontend Mentor - Huddle landing page with curved sections solution
  

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2).

  

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

- View the optimal layout for the site depending on their device's screen size

  

### Screenshot

  

![Mobile](./screenshots/mobile.png)
![Tablet](./screenshots/tablet.png)
![Desktop](./screenshots/desktop.png)

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

  

To solve the project I had to use new HTML tags as well as CSS concepts that were unknown to me, such as "custom properties", the use of media queris have also been key to being able to view the project on different devices.

  

```html
<picture>
                    <source media="(ming-width:1024px" srcset="./images/bg-section-top-desktop-2.svg">
                    <source media='(min-width: 768px)' srcset="./images/bg-section-top-desktop-1.svg">
                    <source media="(min-width:600px)" srcset="./images/bg-section-top-mobile-2.svg">
                    <img src="./images/bg-section-top-mobile-1.svg" alt="#">
</picture>
```

```css

:root {
    --pink: hwb(322 32% 0%);
    --ligth-pink: hsl(321, 100%, 78%);
    --light-red: hsl(0, 100%, 63%);
    --Very-dark-cyan: hsl(192, 100%, 9%);
    --Very-pale-blue: hsl(207, 100%, 98%);
    --primary-font_family: 'Open Sans';
    --secondary-font_family: Poppins;
    --header-height: 3.5rem;
    --h1-font-size: clamp(1.5rem, 5vw, 3rem);
    --h2-font-size: clamp(1.25rem, 3vw, 2rem);
    --h4-font-size: clamp(.865rem, 3vw, 1.125rem);
    --little-white: #fff;
}

```

  

### Continued development

  

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

  

### Useful resources

  

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.

- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

  

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

  

## Author

  
- Ibrahim Almeyda

- Frontend Mentor - [@Ibrahim-003](https://www.frontendmentor.io/profile/Ibrahim-003)
  
