# four-card-css-grid-mobile-first

# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size



### Links

- Solution URL: [https://github.com/Datok95/four-card-css-grid-mobile-first/tree/main](https://your-solution-url.com)
- Live Site URL: [https://fastidious-cat-d1c4bf.netlify.app/](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I solved this challenge using css grid, it took me a while to finish, and i had to ask chatgpt for solutions

CHATGPT SOLUTION
.flex-container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 10px;
}

.item1 {
    grid-column: 1;
    grid-row: 1 / span 2;
    align-self: center;   /* Centers vertically */
    justify-self: center; /* Optional: centers horizontally */
}

.item2 {
    grid-column: 2;
    grid-row: 1;
}

.item3 {
    grid-column: 2;
    grid-row: 2;
}

.item4 {
    grid-column: 3;
    grid-row: 1 / span 2;
    align-self: center;   /* Optional */
    justify-self: center; /* Optional */
}



### AI Collaboration

When the user is on the PC, I found it very difficult to make the grid design like a diamond shape like the problem, I had to ask ChatGPT and it was very helpful


## Acknowledgments

My first grid solution really proud of the result code, made it almost by myself
