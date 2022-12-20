# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![](./images/Screenshot_final_2022.png)

### Links

- Solution URL: [Link To Solution](https://www.frontendmentor.io/solutions/qr-code-component-KQMqzd9gtn)
- Live Site URL: [QR_Code_Challenge](https://qr-code-app-raw.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

-My first challenge creating a div which would cover the entire screen and serve as a background for the card item. 
The ultimate and most satisfying part of this challenge was applying one of the many 'How To Center a div' solutions. I decided to use flexbox for this because it is simpler and easy for me to remember.

I'm particularly proud of this CSS code snippet that enabled me to place the card item at the center of the page:
```css
.container {
  background-color: hsl(212, 45%, 89%);
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: "Outfit", sans-serif;
  height: 100%;
  width: 100%;
  position: fixed;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
```

### Continued development
Fromm feedback I received on my first submission, I have learned important rules such as:
-img tags should have an alt text
-web pages should have main landmarks e.g. using ```<main>``` instead of ```<div>``` to identify the main content of a page
-web pages should have a level-one heading i.e., ```<h1>```

## Author

- Frontend Mentor - [@EnigmaTechx](https://www.frontendmentor.io/profile/EnigmaTechx)
- Twitter - [@DerryckDX](https://www.twitter.com/DerryckDX)
