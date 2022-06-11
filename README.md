# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Screenshot

![](Screenshot%20(64).png)
![](Screenshot%20(66).png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Javascript functions


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="rating-value"><button type="button" onclick="show(1)">1</button></div>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```
```js
  function show(n) {
    document.querySelector("#ratingSelected").innerHTML = `${n}`
    document.getElementById("submit").style= "visibility: visible;"
  }
```


## Author

- Frontend Mentor - [@Izima01](https://www.frontendmentor.io/profile/Izima01)
- Twitter - [@IzimaObisike](https://twitter.com/IzimaObisike)

