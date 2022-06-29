# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![final](/Screenshot1%20Final.png)
![hover](/Screenshot2.png)
![hover2](/Screenshot3.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

This Challenge was in many ways similar to the previous one. However, I encountered new commands and hand to use google for help.

In this challenge I decided to try changing the font used, as I was unable to do it on the last challenege. I was able to do it and it was very simple actually. Here is what I used:
```css
@font-face {
    font-family: Outfit;
    src: url(https://fonts.google.com/specimen/Outfit);
}
```


Next was using the <span> command in html to have different properties for different blocks of text in a single paragraph. I'm not sure if this is the optimal way to go about it. Coders solve problems and this is how I did it:
```html
<p class="p3"><img src="./images/icon-ethereum.svg" alt="Eth Icon" style="width: 10px;height:11px;"> 0.041 ETH<span class="p4"><img src="./images/icon-clock.svg" style="width: 10px;height:11px;"> 3 days left</span></p> 
```

After that, I had to play around with the :hover command in css. This command basically executes instructions when you hover on an the element you called. For example:
```css
.p1:hover{
    color: aqua;
    cursor: pointer;
}
```

### Continued development

This is my second html/css challenege. I am still discovering things in both languages. It is going smoothly and better than I expected. 
Needless to say these a very basic challeneges and I should do few more and then move on to add other languages in the mix.
My main goal is to do 10 newbie challenegs and then create my own basic website. After that, move to the next level of challeneges.



## Author

Abdel Fattah Ibrahim.

## Acknowledgments

Developer Direction community. 
Josh for taking the time to lead the course help.
Kyle for introducing me to the group.
All the other members of the community for their support.
