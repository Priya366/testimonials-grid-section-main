# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)
![Screenshot 2022-03-11 at 15-23-48 Testimonials](https://user-images.githubusercontent.com/96676832/157845387-254a3196-cef3-47e7-aeb2-0756332c7936.png)



### Links

- Solution URL: (https://github.com/Priya366/testimonials-grid-section-main)
- Live Site URL:(https://grid-testimonial-sec.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned

This part was a bit difficult at first(because of shift of testimonials for desktop version) but after thorough search and grasping the full understanding of grid-column and row-spaning, it seems easier now.

```css
 .grid-col-span-2 {
        grid-column: span 2;
    }
 .grid-child:last-child {
        grid-column-start: 4;
        grid-row: 1/ span 2;
    }

```

### Useful resources

- (https://youtu.be/rg7Fvvl3taU)- This is an amazing tutorial by Kevin Powell which helped me finally understand CSS Grid. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Priya garg](https://www.your-site.com)
- Frontend Mentor - [@Priya366](https://www.frontendmentor.io/profile/Priya366)
- Twitter - [@Priyaga89393017](https://twitter.com/Priyaga89393017)
