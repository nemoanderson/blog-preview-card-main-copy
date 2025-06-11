# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Preview of my design](/design/preview.png)

### Links

- Solution URL: [Preview solution URL here](https://www.frontendmentor.io/solutions/blog-preview-card-N0xV5Bz0Zq)
- Live Site URL: [Preview live site URL here](https://nemoanderson.github.io/blog-preview-card-main-copy/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:
Just finished W3school HTML and they Note: Always specify the width and height of an image. If width and height are not specified, the web page might flicker while the image loads.

https://www.w3schools.com/html/html_images.asp

```html
<div class="card__image">
  <img
    src="./assets/images/illustration-article.svg"
    alt="illustration"
    style="width: 100%"
  />
</div>
```

I couldn't figure out why the image borders wasn't rounding. I was applying boder-radius to only the card class. That's like rounding the photo album you put the picture in and expecting it to round the picutures corners also. 

```css
.card img {
  border-radius: 10px;
}
```

### Continued development

The first versions of all these challenges will be HTML5, CSS3, and vanilla JavaScript. v2 will include SASS or LESS as I finish these challeges and finish the learning for one of these CSS preprocessors and then Bootstrap & Typescript for v3.

### Useful resources

- [w3 School HTML Tutorials.](https://www.w3schools.com/html/default.asp) - I just went back to basics to see if there was any gaps in my learning and no suprise, there was. I breezed though most of the learning but there were some things that I'm glad that I learned. On to the CSS.
- [Mr. Coder YouTube](https://www.youtube.com/watch?v=5BBYPntB-GY) - I checked out how Mr. Coder went about doing a challenge I already completed to see his workflow.

## Author

- Website - [Marketaur](https://www.marketaur.com)
- Frontend Mentor - [@nemoanderson](https://www.frontendmentor.io/profile/nemoanderson)
