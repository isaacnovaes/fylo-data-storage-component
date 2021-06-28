# Frontend Mentor - Fylo data storage component solution

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

![Mobile](./screenshot.jpg)
![Desktop](./screenshot.jpg)


### Links

- [Live Site](https://your-live-site-url.com)

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
Also, although I don't know JS, I wrote a few lines of JS so that the input range value could be displayed automatically as it changes upon user action. 
```js
var slider = document.getElementById("slider");
      var progressBar = document.getElementById("progressBar");
      progressBar.style.width = .082*slider.value + "%";
      var showValue1 = document.getElementById("showValue1");
      var showValue2 = document.getElementById("showValue2");

      slider.oninput = function () {

        showValue1.innerHTML = slider.value;
        showValue2.innerHTML = 1000-slider.value;
        progressBar.style.width = slider.value*.083 + .05 + "%" ;
        
      }
```

### Continued development

This challenge was pretty easy to complete, however, without JS, I wouldn't be able to finish it. Therefore, I plan to use all my summer holiday to study JS full time.




