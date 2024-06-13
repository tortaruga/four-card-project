# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

This solution uses only Flex and no grids. I'm satisfied enough with the way it turned out, it's responsive and simple enough to implement. I'll try to reach the same result using grids.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/Screenshot%202024-06-13%20at%2018-04-30%20Frontend%20Mentor%20Four%20card%20feature%20section.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/responsive-cards-with-flex-187MQAd38b](https://www.frontendmentor.io/solutions/responsive-cards-with-flex-187MQAd38b)
- Live Site URL: [https://tortaruga.github.io/four-card-project/](https://tortaruga.github.io/four-card-project/)

### Built with

- Semantic HTML5 markup
- CSS 
- Flexbox
- Mobile-first workflow

### What I learned

It's not exactly something I learned, because I already used something similar to it before, but I'm proud of this solution to change the color of each section without repeating the same code four times:

```css
section {
    background: linear-gradient(var(--bg) 2%, transparent 2%), white;
}

.supervisor {
    --bg: var(--cyan);
}

.team-builder {
    --bg: var(--red);
}

.karma {
    --bg: var(--orange);
}

.calculator {
    --bg: var(--blue);
}

```
### Continued development

I think this solution works well enough but I would like to get better at using grids so I think I will try to code a version with grids instead. 

## Author

- Frontend Mentor - [@tortaruga](https://www.frontendmentor.io/profile/tortaruga)
