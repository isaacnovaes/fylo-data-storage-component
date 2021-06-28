# Frontend Mentor - Fylo data storage component solution

![Desktop](/design/desktop.png)

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). 

## Table of contents

- [Frontend Mentor - Fylo data storage component solution](#frontend-mentor---fylo-data-storage-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

[Mobile](/design/mobile.png)

[Desktop](/design/desktop.png)


### Links

- [Live Site](https://fylo-data-storage-dark.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- SASS
- Animation

### What I learned

In this challenge, I have learned how to style the range form input type, which was a style that I have first seen during my short web develop journey. The respective code can be seen below:

To see how you can add code snippets, see below:

```css
input[type=range]{
                    display: block;
                    -webkit-appearance: none;
                    width: 80%;
                    height:20px;
                    margin: 20px auto;   
                    border-radius: 10px; 
                    background-color:$very-dark-blue;                
                    //Here, the slider track is styled

                    &::-webkit-slider-thumb {
                        -webkit-appearance: none;
                        height: 20px;
                        width: 20px;
                        cursor: pointer;    
                        background-color: white; 
                        border-radius: 10px;                       
                        position: relative;
                        z-index: 2;
                        //Here, the thumb is styled
                    }
}
```

### Continued development

This challenge was pretty easy to complete, however, I felt that if I knew JS, I would make the website much more interactive. Therefore, I am more and more stimulated to start studying JS, which will happen when my exam period finishes at my university.




