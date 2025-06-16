## Lab 3.3: Developing with Bootstrap

#### First Challenge – QR Code Component

This project is a refactored version of my origina QR Code Component card (https://github.com/urmee04/QR-Code-Component-Romana-Akter) built with custom CSS. As part of a Lab- the goal was to convert this component to use Bootstrap utility classes and components to improve consistency, responsiveness, and maintainability across projects.


##### Objectives

- Refactor an existing project using Bootstrap’s utility classes.
- Use Bootstrap components to replace custom-styled elements.
- Apply Bootstrap’s grid system for responsive layouts.
- Demonstrate the ability to leverage Bootstrap documentation for efficient development.

##### Features

- Responsive layout for mobile and desktop.
- Semantic HTML structure using `<article>`, `<header>`, `<main>`, and `<footer>`.
- CSS custom properties (`:root`) for easy color management.

##### Technologies Used

- Semantic HTML5
- Bootstrap 5.3.3
- Google Fonts (Figtree: weights 400, 700)

##### How to Use

1. Clone the repository or download the ZIP.
2. Be sure to maintain the folder structure.
3. Open `index.html` in your browser to view the card.

- git clone https://github.com/urmee04/QR-Code-Component-Bootstrap-Romana-Akter
- cd qr-code-component-bootstrap
- cd index.html
- open index.html

#### Design Specifications
- Mobile width: 375px

- Desktop width: 1440px

- Font family: Outfit

- Font weights: 400, 700

###### Colors:

- White: hsl(0, 0%, 100%)
- Slate 300: hsl(212, 45%, 89%)
- Slate 500: hsl(216, 15%, 48%)
- Slate 900: hsl(218, 44%, 22%)

##### Accessibility
- Images have descriptive alt attributes.

##### Reflections
**1. Challenges I faced when refactoring to Bootstrap:**

- Matching custom padding, spacing, and font styles using only Bootstrap classes.

- Recreating a custom box shadow wasn’t possible with Bootstrap alone—had to use inline CSS.

- Balancing between Bootstrap utility classes and minimal custom styling was tricky.

**2. How Bootstrap simplified my styling:**

- Saved time by using classes like d-flex, justify-content-center, and fw-bold instead of writing CSS.

- Made layouts responsive faster with grid and spacing utilities.

- Reduced the amount of custom CSS and made HTML cleaner.

**3. When I would use custom CSS instead of Bootstrap:**

- When the design requires exact styling or unique hover effects (e.g., a “card pop” on hover).

- For performance optimization—avoiding unused Bootstrap code.

- When creating animations or interactions not supported by Bootstrap.








