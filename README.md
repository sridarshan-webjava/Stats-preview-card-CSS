# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

Desktop View

![](./Screenshot-Desktop.png)

Mobile View

![](./Screenshot-Mobile.png)

### Links

- Solution URL: [Solution](https://github.com/sridarshan-webjava/Stats-preview-card-CSS)
- Live Site URL: [Live Site](https://sridarshan-webjava.github.io/Stats-preview-card-CSS/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Major Key Learnings

- Using CSS BEM Convention
- Using CSS Variables

```html
<section class="stats">
  <div class="stats__image-container"></div>
  <div class="stats__main-content stats--flow-content"></div>
</section>
```

```css
:root {
  --spacing: 1rem;
}

.stats {
  border-radius: calc(var(--spacing) * 0.5);
}

.stats__main-content {
  padding: calc(var(--spacing) * 1.5);
}
```

### Continued development

- Using CSS Animations for the stats

## Author

- Website - [Sridarshan](https://sridarshan-webjava.github.io/Stats-preview-card-CSS/)
- Frontend Mentor - [@sridarshan-webjava](https://www.frontendmentor.io/profile/sridarshan-webjava)
