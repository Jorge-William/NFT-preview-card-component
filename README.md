# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - NFT preview card component solution](#frontend-mentor---nft-preview-card-component-solution)
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
  - [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
![Desktop](https://user-images.githubusercontent.com/19416864/144131863-52aff674-a6a9-44f7-bcd4-11be26e08e33.png)
![Mobile](https://user-images.githubusercontent.com/19416864/144131895-9e068c8f-91ef-4c70-b72b-69abb636bac6.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

The hardest part on this project was show the eye icon on mouse hover over card main image.<br>
I've use the background-image properties of css and the page was estructured with only html markup.

Some code I'm proud of</h1>

```css

#main-image {
  background-image: url('../images/image-equilibrium.jpg');
  background-position: center center;
  background-size: cover;
  height: 302px;
  width: 302px;
  border-radius: 8px;
}

div#main-image:hover{
  background-image: linear-gradient(rgba(0, 255, 255, 0.4),rgba(0, 255, 255, 0.4)), url('../images/icon-view.svg'), url('../images/image-equilibrium.jpg');
  background-repeat: no-repeat;
  background-size: 100%, 20%, 100%;  
  background-position: center;  
}

```


### Continued development

I want to continue improving this code because i know that how much more i pratice more i will learn.

### Useful resources

- [CSS tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me for remember about Flexbox
- [W3Schools](https://www.w3schools.com/default.asp) - Some tips on css.

## Author

- Website - [Jorge William](https://github.com/Jorge-William)
- Frontend Mentor - [@jorge-william](https://www.frontendmentor.io/profile/Jorge-William)
- Twitter - [@Jorge_Willi4m](https://twitter.com/Jorge_Willi4m)


## Acknowledgments

- The tips Milen wrote on the forum helped me a lot. - [Milen Nenkov](https://twitter.com/NenkovMilen)

