# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [GitHub Repository](https://github.com/noob-coder6/testimonials-grid-section)
- Live Site URL: [Live Demo](https://noob-coder6.github.io/testimonials-grid-section)

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS variables)
- Flexbox for card header layout
- CSS Grid for overall layout
- Mobile-first responsive workflow
- BEM naming convention

### What I learned

This project helped me solidify my understanding of CSS Grid and how to create complex, responsive layouts. I particularly enjoyed working with grid-column spanning and grid-row placement to create the asymmetric layout on desktop.

Key learnings include:

**CSS Grid spanning for varied card sizes:**
```css
.card--violet {
  grid-column: span 2;
}

.testimonial-grid > article:last-child {
  grid-column: 4 / 5;
  grid-row: 1 / 3;
}
```

**Using CSS custom properties for maintainable theming:**
```css
:root {
  --clr-primary-violet: hsl(263, 55%, 52%);
  --clr-primary-gray-blue: hsl(217, 19%, 35%);
}
```

**Modern centering technique with CSS Grid:**
```css
body {
  display: grid;
  place-content: center;
  min-height: 100vh;
}
```

I also learned how to use opacity to create visual hierarchy without changing colors, and how the `gap` property simplifies spacing in both Grid and Flexbox layouts.

### Continued development

In future projects, I want to:

- Explore more advanced CSS Grid techniques like grid-template-areas for even more intuitive layouts
- Practice creating more complex responsive patterns with multiple breakpoints
- Improve my understanding of accessibility best practices for testimonial sections
- Experiment with CSS animations for card hover effects
- Learn to optimize images and implement lazy loading for better performance

## Author

- GitHub - [@noob-coder6](https://github.com/noob-coder6)
- Frontend Mentor - [@noob-coder6](https://www.frontendmentor.io/profile/noob-coder6)