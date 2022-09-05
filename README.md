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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

I am trying to get more familiar with Flexbox. So I used it to do the layout. I know the codes are not perfect, but I am happy to see that I am progressing. 
In the past, I usually got stuck at aligning two separate paragraphs vertically. But this time, I can use Flex to solve the problem fast: 

```css
.price{
    display: flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: center;
```


### Continued development

I would like to figure out how to make the site more responsive, since the width of the card doesn't adjust to the width of the window.

### Useful resources

- [Flexbox Froggy](https://flexboxfroggy.com/) - The game helps me to practice the basics of flexbox. 
