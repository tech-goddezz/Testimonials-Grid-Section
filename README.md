# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials Grid Section Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

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
* [Acknowledgments](#acknowledgments)

---

## Overview

### The challenge

Users should be able to:

* View the optimal layout for the site depending on their device’s screen size
* See consistent spacing, alignment, and card hierarchy
* Experience a clean, responsive design that adapts smoothly from mobile to desktop

---

### Screenshot

![](./screenshot.jpg)

*(Add your final screenshot here — recommended: take a full-width capture of your final layout in Firefox or with a tool like FireShot.)*

---

### Links

* **Solution URL:** (https://github.com/tech-goddezz/Testimonials-Grid-Section.git)
* **Live Site URL:** (https://testimonials-grid-section-umber.vercel.app/)

---

## My process

### Built with

* **Semantic HTML5 markup**
* **CSS custom properties**
* **CSS Grid**
* **Flexbox** (for alignment inside cards)
* **Mobile-first workflow**
* **Google Fonts** – *Barlow Semi Condensed*

---

### What I learned

This project strengthened my understanding of **CSS Grid layout systems** and **responsive composition**.
I learned how to create complex multi-column and multi-row grids that still adapt perfectly to smaller viewports.

I also refined how I manage spacing and hierarchy using **CSS variables**, allowing the design to remain consistent across all card variations.

Here’s a quick example of my approach to the grid structure:

```css
.testimonials-grid {
  display: grid;
  grid-template-areas:
    "daniel daniel jonathan kira"
    "jeanette patrick patrick kira";
  gap: 1.5rem;
}
```

And my variable setup for consistency:

```css
:root {
  --clr-primary: hsl(263, 55%, 52%);
  --clr-secondary: hsl(217, 19%, 35%);
  --clr-neutral-100: hsl(0, 0%, 100%);
  --clr-neutral-200: hsl(210, 46%, 95%);
  --fs-base: 0.8125rem;
  --fw-medium: 500;
  --fw-bold: 600;
}
```

This helped maintain a **clear visual rhythm** across different card backgrounds.

---

### Continued development

In future projects, I want to:

* Explore **CSS clamp()** for fluid font sizing and spacing.
* Introduce **SASS/SCSS** to manage variables and mixins more efficiently.
* Focus more on **accessibility** by refining contrast ratios and semantic HTML structure.
* Learn advanced **CSS Grid responsive techniques** for even more dynamic layouts.

---

### Useful resources

* [CSS Tricks: A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) — An excellent reference for mastering CSS Grid layout.
* [Kevin Powell’s YouTube Channel](https://www.youtube.com/kepowob) — Practical explanations and visual demos of CSS layout challenges.
* [Frontend Mentor Community](https://www.frontendmentor.io/community) — Great for learning from others’ solutions and best practices.

---

## Author

* **Website:** [TechUp with LIZ](#)
* **Frontend Mentor:** [@TechUpwithLIZ](https://www.frontendmentor.io/profile/TechUpwithLIZ)
* **Twitter:** [@TechUpwithLIZ](https://twitter.com/TechUpwithLIZ)

---

## Acknowledgments

A big thanks to **Frontend Mentor** for providing this amazing design challenge.
Also, special appreciation to the CSS community and online creators who constantly share knowledge and inspire improvement in front-end development skills.

