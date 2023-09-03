# product-preview-card-component 

This is my solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Video Preview](#video-preview)
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
- See hover and focus states for interactive elements

### Video Preview

[Responsive product card component.webm](https://github.com/sarahjq-s/product-preview-card-component/assets/127857067/153784af-9115-4c28-b9d4-837538d759a7)


### Links

- Solution URL: [Github Repo](https://github.com/sarahjq-s/product-preview-card-component)
- Live Site URL: [Product Preview card component](https://snazzy-moonbeam-30a84e.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

There were 2 provided images for the different layouts. I wasn't sure how I would place the images in the HTML to show in the desktop and mobile views. I figured that I could make an id tag for the image then change the background images in the CSS. 
```html
<div id="img-container"></div>
```
for desktop layout

```css 
#img-container{
    background: url("images/img-product-desktop.jpg") no-repeat center/cover;
    border-radius: 10px 0 0 10px;
}
```
for mobile layout

```css 
#img-container{
        background: url("images/img-product-mobile.jpg") no-repeat center/cover;
        border-radius: 10px 10px 0 0;
        width: 350px;
        height: 240px;
    }
}
```

### Continued development

I'm trying to learn the technical terms and how to communicate better. Moreover, I'm still struggling with flexbox but I'm slowly understanding the concept with this challenge. I used the Inspect Tool to assist me with understanding the design layout and the concept of flexbox. 

I would appreciate feedback on a better solution on how to make and position the card component. I'm also learning a mobile-first approach and would like anyone to share any tip or their workflow. I had faced some challenges with this approach and although there was not a major change in the layout after completing the desktop layout, it would be helpful to know a better workflow.

### Useful resources

- [An Interactive Guide to Flexbox by Josh Comeau](https://www.joshwcomeau.com/css/interactive-guide-to-flexbox/) - This helped me understand flexbox better.

## Author

- LinkedIn - [Sarah Saballa](https://www.linkedin.com/in/sarah-saballa-315053185/)
- Frontend Mentor - [@sarahjq-s](https://www.frontendmentor.io/profile/sarahjq-s)
- Instagram - Documenting #100daysofCode- [@sarahjq.s_dev](https://www.instagram.com/sarahjq.s_dev/)
