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
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![image](https://github.com/TwinkleByte/Blog-preview-card/assets/91601992/9f520014-1c96-4f02-8b55-db3c49f2d389)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Solution](https://github.com/TwinkleByte/Blog-preview-card)
- Live Site URL: [Live Site](https://lonebrokeboy.github.io/Blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I learned box shadow and transition.

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
.card {
    background-color: var(--card-bg);
    display: grid;
    grid-template-rows: 231px 56px 33px 41px 90px 64px;
    border: solid 1px var(--border-color);
    width: 382px;
    height: 514px;
    margin-top: 217px;
    border-radius: 25px;
    box-shadow: 9px 9px black;
    transition: box-shadow 0.10s ease-in-out;
}
.card:hover {
    box-shadow: 17px 17px black;
}
```

## Author

- Frontend Mentor - [@TwinkleByte](https://www.frontendmentor.io/profile/TwinkleByte)
- Github - [@TwinkleByte](https://github.com/TwinkleByte)
