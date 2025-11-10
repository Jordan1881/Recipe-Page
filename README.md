# Frontend Mentor - Recipe Page Solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
* View the optimal layout for the recipe page depending on their device's screen size.
* See hover states for all interactive elements on the page.

### Screenshot

![A mockup screenshot of the Simple Omelette Recipe page on desktop](../Recipe-Page/design/desktop-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/Jordan1881/Recipe-Page.git)


## My process

### Built with

* Semantic HTML5 markup
* CSS custom properties (Variables for all colors and fonts)
* Flexbox (for primary layout and component alignment)
* Mobile-first workflow
* Custom Fonts: **Young Serif** (Headings) and **Outfit** (Body text)

### What I learned

Working on this project reinforced my knowledge of CSS variables and custom styling for structural HTML elements:

* **Effective Use of CSS Variables:** Defined and utilized all colors and font families (Young Serif and Outfit) as CSS custom properties in the `:root` selector for maintainability and easy theming, following the provided style guide.
* **Semantic and Accessible HTML Structure:** Ensured the use of appropriate semantic tags (`<h1>`, `<h2>`, `<ul>`, `<ol>`, `<table>`, etc.) to clearly structure the recipe components (Ingredients, Instructions, Nutrition) for better accessibility.
* **Custom Table Styling:** Successfully styled the **Nutrition** table to match the design, focusing on creating subtle dividers using `border-bottom` on `<th>` and `<td>` elements and styling the nutritional values with a custom font weight and color:
    ```css
    .nutrition td {
      border: none;
      border-bottom: 1px solid var(--stone-150);
      /* ... other styles ... */
      color: var(--brown-800);
      font-weight: var(--font-weight-bold);
    }
    ```
* **Font Integration:** Managed custom font face declarations (`@font-face`) for Young Serif and multiple weights of Outfit to ensure accurate typography.

### Continued development

* **Advanced Responsiveness:** I plan to introduce more complex Media Queries in future projects to perfectly handle intermediate breakpoints (e.g., tablet views) rather than relying solely on the mobile-first approach.
* **CSS Grid Integration:** I want to practice implementing CSS Grid for component layouts that require two-dimensional alignment, such as the list items or the container itself.
* **Accessibility (A11y) Refinement:** Further exploration of ARIA attributes and better focus management for enhanced keyboard navigation and overall accessibility compliance.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

---

**Next Steps:**

Remember to **replace the placeholder links** and **update your author details** in the final file! Would you like me to generate a template for a different section, like a more detailed "Useful resources" list?