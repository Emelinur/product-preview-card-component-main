
# Frontend Mentor - Product preview card component solution
![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)
## Welcome! 👋
This is my solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

I had built this project before, but this time I updated it with **style guide tokens (colors, typography, spacing)**, **semantic HTML**, and **responsive clamp-based scaling**.  

---

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

---

## Overview

### The challenge
Users should be able to:

- View the optimal layout depending on their device's screen size  
- See hover and focus states for interactive elements  

### Screenshot
![](./images/screenshot.jpg)

### Links
- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-card-with-css-media-QMXS6BbY40)  
- Live Site URL: [Add live site URL here](https://emelinur.github.io/product-preview-card-component-main/)  

---

## My process

### Built with
- Semantic **HTML5**  
- **CSS custom properties** (style guide tokens)  
- **CSS Grid** + Flexbox  
- **clamp()** for fluid typography & spacing  
- Mobile-first workflow  
- Accessible markup (`button`, `alt`, `focus-visible`)  

### What I learned
I practiced updating an old project using a **design system approach**.  
- Created tokens for **colors, spacing, typography**.  
- Used `clamp()` to make font sizes and spacing responsive without many media queries.  
- Learned the difference between **vh** and **svh**:  
  - `vh` = viewport height (can jump on mobile when browser UI shows/hides).  
  - `svh` = “small viewport height”, more stable on mobile.  

Example of a fluid spacing token:
```css
--space-200: clamp(1rem, 0.8rem + 1vw, 1.5rem);
 ```

 ## Author
 - Frontend Mentor - [@Emelinur](https://www.frontendmentor.io/profile/Emelinur)

**Have fun building!** 🚀
