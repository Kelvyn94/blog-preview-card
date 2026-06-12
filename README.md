# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor]. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

<img width="1358" height="573" alt="image" src="https://github.com/user-attachments/assets/db3066d1-40fc-4b6d-b413-065837eabf50" />


_Add a screenshot of your finished solution here_

### Links

- Solution URL: https://github.com/Kelvyn94/blog-preview-card
- Live Site URL: https://kelvyn94.github.io/blog-preview-card/ 

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS Variables)
- Flexbox
- Mobile-first workflow
- Google Fonts (Figtree)

### What I learned

This project reinforced several fundamental web development concepts:

**1. CSS Box Shadow for Depth**
Creating the card's 3D effect using multiple box shadows:

```css
.blog-card {
  box-shadow: 8px 8px 0 var(--gray-950);
  transition: box-shadow 0.3s ease;
}

.blog-card:hover {
  box-shadow: 12px 12px 0 var(--gray-950);
}
```
