# Frontend Mentor - Recipe page solution

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

### Screenshot

![](./screenshots/desktop-design.jpg)
![](./screenshots/mobile-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

Working on this project taught me how to effectively manipulate lists (<ul> and <ol>) and tables (<table>) using CSS for better presentation. I learned to style list items for better readability by controlling padding, font sizes, and colors. Additionally, I explored how to enhance tables by adjusting borders, cell spacing, and typography, which improved both the structure and the visual appeal of the nutritional information section.

```html
<ul class="ingredients-list">
  <li>
    <p class="ingredients-text">2-3 large eggs</p>
  </li>
  <li>
    <p>Salt, to taste</p>
  </li>
  <li>
    <p>Pepper, to taste</p>
  </li>
  <li>
    <p>1 tablespoon of butter or oil</p>
  </li>
  <li>
    <p>Optional fillings: cheese, diced vegetables, cooked meats, herbs</p>
  </li>
</ul>
```

````html
<ol>
  <li>
    <strong>Beat the eggs:</strong>
    <p>
      In a bowl, beat the eggs with a pinch of salt and pepper until they are
      well mixed. You can add a tablespoon of water or milk for a fluffier
      texture.
    </p>
  </li>

  <li>
    <strong>Heat the pan:</strong>
    <p>Place a non-stick frying pan over medium heat and add butter or oil.</p>
  </li>

  <li>
    <strong>Cook the omelette:</strong>
    <p>
      Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to
      ensure the eggs evenly coat the surface.
    </p>
  </li>

  <li>
    <strong>Add fillings (optional):</strong>
    <p>
      When the eggs begin to set at the edges but are still slightly runny in
      the middle, sprinkle your chosen fillings over one half of the omelette.
    </p>
  </li>

  <li>
    <strong>Fold and serve:</strong>
    <p>
      As the omelette continues to cook, carefully lift one edge and fold it
      over the fillings. Let it cook for another minute, then slide it onto a
      plate.
    </p>
  </li>

  <li>
    <strong>Enjoy:</strong>
    <p>Serve hot, with additional salt and pepper if needed.</p>
  </li>
</ol>
``` 

```html
<table>
  <tr>
    <td>Calories</td>
    <td>277kcal</td>
  </tr>

  <tr>
    <td>Carbs</td>
    <td>0g</td>
  </tr>

  <tr>
    <td>Protein</td>
    <td>20g</td>
  </tr>

  <tr class="last-row">
    <td>Fat</td>
    <td>22g</td>
  </tr>
</table>
```

```css
.preparation {
  margin-top: 15px;
  background-color: hsl(330, 100%, 98%);
  border-radius: 7px;
}
````

```css
.instructions ol {
  font-size: 7px;
  padding-left: 12px;
}
```

```css
table {
  font-family: "outfit-regular";
  margin: 10px 0;
  width: 100%;
  border-collapse: collapse;
  line-height: 2.5;
}
```

### Continued development

- Responsive Design: Optimize for larger screens and add breakpoints for tablets to improve layout responsiveness.

- Accessibility: Enhance accessibility with ARIA labels, better color contrast, and keyboard navigation support.

- Interactive Elements: Add collapsible sections for details, and include a "print recipe" button for convenience.

- Dark Mode: Implement a dark mode toggle to improve readability in low-light conditions.

- Additional Recipes: Support multiple recipes with navigation options and a search bar for easy access.

- Animations & Transitions: Add subtle animations and transitions for a more engaging user experience.


## Author

- Frontend Mentor - [@Tainicknack0505](https://www.frontendmentor.io/profile/Tainicknack0505)
- GitHub - [@Tainicknackz](https://www.github.com/Tainicknackz)
