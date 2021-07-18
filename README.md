# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Desktop Design 
![fylo-data-storage-component-master_index html (4)](https://user-images.githubusercontent.com/86558336/126078625-c8852723-b024-4da2-aea8-d62b53d946c3.png)

Mobile Design
![screencapture-fylo-data-storage-component-master-index-html-2021-07-18-22_42_33](https://user-images.githubusercontent.com/86558336/126078706-ac3a5c79-3939-48f5-96eb-37980507d12f.png)

Active States
![127 0 0 1_5500_fylo-data-storage-component-master_index html (6)](https://user-images.githubusercontent.com/86558336/126078834-550ed8df-e9c3-4307-9736-977c9e517ef4.png)

### Links

- Solution URL: [Code on Github](https://github.com/abdo-kotb/fylo-data-storage-component)
- Live Site URL: [live site URL](https://abdo-kotb.github.io/fylo-data-storage-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Animation
- CSS Normalize
- Google Fonts

### What I learned

I learned to create a number counter animation by a method that is not yet fully supported but it made the page look much better.
```css
@property --num {
  syntax: "<integer>";
  initial-value: 185;
  inherits: false;
}
.remaining {
  animation: counter 2s ease-in-out;
  counter-reset: num var(--num);
}
.remaining::before {
  content: counter(num);
}

@keyframes counter {
  from {
    --num: 999;
    opacity: 0;
  }
  to {
    --num: 185;
  }
}
```

### Useful resources
[Number counter animation example](https://css-tricks.com/animating-number-counters/) - I got the idea of making a number counter animation and hoped that there was a way to create something looks good with pure CSS and this article was the best thing that I have found that explains the old methods and the new methods. It is an amzaing artice and I'd recommend it to anyone still learning this concept.

## Author

- Git hub - [abdo-kotb](github.com/abdo-kotb)
- [Linkedin](https://www.linkedin.com/in/abdulrhman-mohammed-5687781b5/)
- Frontend Mentor - [@abdo-kotb](https://www.frontendmentor.io/profile/abdo-kotb)

Abdulrhman Kotb
