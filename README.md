# Frontend Mentor - Blog Preview Card Solution

This is my solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). It's a small yet impactful exercise that helped me solidify my understanding of responsive layout, typography, and CSS fundamentals.

## Table of contents

* [Overview](#overview)

  * [The challenge](#the-challenge)
  * [Screenshot](#screenshot)
  * [Links](#links)
* [My process](#my-process)

  * [Built with](#built-with)
  * [What I learned](#what-i-learned)
  * [Continued development](#continued-development)
  * [Useful resources](#useful-resources)
* [Author](#author)

---

## Overview

### The challenge

Users should be able to:

* See hover states for all interactive elements on the page
* View the card on mobile and desktop screen sizes

### Screenshot

![Desktop Screenshot](./desktop-design.jpg)
![Mobile Screenshot](./mobile-design.jpg)

### Links

* **Solution URL**: [GitHub Repo](https://github.com/readollar/blog-card)
* **Live Site URL**: [Live Demo](https://Readollar.github.io/blog-card)

---

## My process

### Built with

* Semantic HTML5
* CSS custom properties (variables)
* Flexbox layout
* Mobile-first workflow
* Custom local font (Figtree)

### What I learned

This project helped reinforce my knowledge of layout and spacing using Flexbox. I also practiced linking and loading a custom local font without relying on Google Fonts:

```css
@font-face {
  font-family: 'Figtree';
  src: url('./assets/fonts/Figtree-VariableFont_wght.woff2') format('woff2');
  font-weight: 500 800;
  font-display: swap;
}
```

I also improved my understanding of how hover states can enhance usability and visual feedback with transitions:

```css
.card:hover {
  box-shadow: 12px 12px 0px black;
  transition: box-shadow 0.2s ease;
}
```

### Continued development

I’d like to improve in the following areas in future projects:

* Exploring alternative layout systems like CSS Grid
* Improving accessibility (ARIA roles, contrast ratios, etc.)
* Adding animations with better performance practices

### Useful resources

* [CSS Flexbox Guide (MDN)](https://developer.mozilla.org/en-US/docs/Web/CSS/flex)
* [Frontend Mentor Community](https://www.frontendmentor.io/)
* [The Markdown Guide](https://www.markdownguide.org/)

---

## Author

* Website – Coming soon
* Frontend Mentor – [@readollar](https://www.frontendmentor.io/profile/readollar)
* GitHub – [@readollar](https://github.com/readollar)
