# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - FAQ accordion card solution](#frontend-mentor---faq-accordion-card-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

- #### Desktop View
    <div style="display: flex; justify-content: center; margin-bottom: 50px;">
      <a href="https://imgur.com/GgDpnwt"><img src="https://i.imgur.com/GgDpnwt.gif" title="source: imgur.com" / width="200"></a>
    </div>

    #### Desktop Design
    <div style="display: flex; justify-content: center; margin-top: 10px;">
      <a href="https://imgur.com/nv7pwHE"><img src="https://i.imgur.com/nv7pwHE.gif" title="source: imgur.com" /></a>
    </div>

### Links

- Solution URL: [Repository](https://github.com/GustavoMont/faq-accordion-card-main)
- Live Site URL: [See by yourself 🤓👀](https://gustavomont.github.io/faq-accordion-card-main/)

## My process
  When I started the challenge I didn't have no idea if it would be difficult for me or not, but I knew that I'd finish it 🧐😼. And I saw that it have a bonus challenge: don't use JS 🤔😲. And I tried it 🧐.
  
    First I had some problem's about footer position. I solved it when I search, and discovered if I use position and display flex it'd be on bottom ever. So first problem solved 😎.

    Another problem was background position in desktop and mobile design 😑😑. I think I solved better in mobile design 📱, in desktop design 💻, sadly, it have a little problem that it still change position while the card container get longer, I accept sugestion to make it better 😁.

    I already have use ✅ checkbox to do some different things like: a modal and a reponsive menu, so I just had to search how to use it for a wrapper, without use JS, only using CSS 🤓. Acctually, was one of things I do that felt most proud about 😄😎. 

    The last problem would be change the images when the width screen get longer, and without use JS, AGAIN 🤦🏽‍♂️🤦🏽‍♂️. But with 5 minutes of searching 🔍, I discovered that it's just use 'content: ' property on css. So I used it, and I get change image 😎. Image is right but not its position 🤦🏽‍♂️. And I used 'display: grid' on card-container and after some tests I got finish the desktop design. 

    In this challenge I could pratice several css skills and I'm so happy to finish it. 😎😁


### Built with

- Semantic HTML5 markup 
- CSS custom properties
- Flexbox
- CSS Grid
  
### What I learned

  I learned so much about the CSS power 🤯🤯. The 'content: ' property and about use CSS grid. My mind just blowing using it. Change the html items place independently of its position in html source 🤯🤓. 

```html
<h1>Some HTML code I'm proud of</h1>
  <div class="card-container">
      <div class="header">
        <img src alt="Logo" id="main">
      </div>
```

```css
/* I really like this */
.wrapper {
    display: none;
}
.wrapper:checked + .question {
    font-weight: 700;
}
.wrapper:checked + .question  img{
    transform: rotate(180deg);
}
.wrapper:checked + .question + .answer{
    opacity: 1;
    display: block;
} 
```
### Continued development

I want to pratice more about CSS Grid and try to make the designs more responsive.  I really need to pratice it I know that it's so important !!!

### Useful resources

- [About change image whithou JS](https://stackoverflow.com/questions/18032220/css-change-image-src-on-imghover) - This helped me for change image src without JS, and I thinked better use it for responsive than use JS. I really liked this property and will use it going forward
- [CSS GRID](https://www.youtube.com/watch?v=HN1UjzRSdBk&t=1836s) - This is an amazing video, it's in portuguese, and helped me so much about the CSS GRID. I'd recommend it to anyone still learning this concept.  

## Author

- Frontend Mentor - [@GustavoMont](https://www.frontendmentor.io/profile/GustavoMont)
- Instagram - [@gust_mont](https://www.instagram.com/gust_mont/)



