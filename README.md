# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This was a very fun project, I was able to learn as I go and pick up new techniques like using the linear gradient property or expererimenting with the box shadow. I also was able to get a better understanding of previous skills that I've used like custom css properties, flex box, and semantic HTML. I hope you enjoy the project as much as i did while making it.

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](assets/images/Screenshot%202023-07-19%20at%205.05.58%20PM.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I took extra time to prep for this project in order to get the custom properties set up, I also set up my HTML so that it was optimal for the flex box that i planned on using for this project.

```html
<div class="red-box">
  <div class="red-title">
    <div class="red-svg"></div>
    <div><p>Reaction</p></div>
  </div>
  <div class="stats">
    <p>80</p>
    <span> / 100</span>
  </div>
</div>
```

```css
:root {
  /* Primary colors */
  --reaction-color-bg: hsl(0, 100%, 67%, 0.1);
  --memory-color-bg: hsl(39, 100%, 56%, 0.1);
  --verbal-color-bg: hsl(166, 100%, 37%, 0.1);
  --visual-color-bg: hsl(234, 85%, 45%, 0.1);
  --reaction-color: hsl(0, 100%, 67%);
  --memory-color: hsl(39, 100%, 56%);
  --verbal-color: hsl(166, 100%, 37%);
  --visual-color: hsl(234, 85%, 45%);
  /* Gradient colors */
  --card-bg-top: hsl(252, 100%, 67%);
  --card-bg-bottom: hsl(241, 81%, 54%);
  --card-bg: linear-gradient(var(--card-bg-top), var(--card-bg-bottom));
  --circle-top: hsla(241, 72%, 46%, 0);
  --circle-bottom: hsla(256, 72%, 46%, 1);
  --circle-bg: linear-gradient(var(--circle-bottom), var(--circle-top));
  /* Neutral colors */
  --white: hsl(0, 0%, 100%);
  --shadow: hsl(241, 100%, 89%);
  --body-bg: hsl(221, 100%, 96%);
  --button: hsl(224, 30%, 27%);
}
```

### Continued development

Right now i plan to keep working on the newbie challenges on Frontend
Mentor. I want to do better at centering things on the page and challenge my self to switch from using flex box and start experimenting with grid a bit.

### Useful resources

- [linear gradient article ](https://css-tricks.com/the-big-gotcha-with-custom-properties/) - This helped me to create the background for the card and also for the circle as well. I really liked the code snippets that were included and also the emmbed section at the end that help me to practice outside of my text editor.

## Author

- Frontend Mentor - [@Hazel-Black](https://www.frontendmentor.io/profile/hazel-black)
- LinkedIn - [Hazel Black](www.linkedin.com/in/hazel-black-a40315237)

## Acknowledgments
