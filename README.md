# Frontend Mentor - Blog Preview Card

This is my solution for the **Blog Preview Card** challenge from Frontend Mentor. The goal of this project was to recreate the provided design while focusing on semantic HTML, modern CSS practices, and responsive design.

## Overview

The project consists of a responsive blog card component featuring:

* Semantic HTML structure
* Flexbox layout
* CSS custom properties (variables)
* Fluid typography using `clamp()`
* Responsive sizing with minimal media queries
* Accessible and maintainable code structure

## Built With

* HTML5
* CSS3
* Flexbox
* CSS Custom Properties
* CSS `clamp()`

## Responsive Typography

This project uses CSS `clamp()` to create fluid typography without relying heavily on media queries.

```css
:root {
    --fs-sm: clamp(12px, 1vw, 14px);
    --fs-md: clamp(14px, 1.5vw, 16px);
    --fs-lg: clamp(20px, 2.5vw, 24px);
}
```

By defining minimum, preferred, and maximum font sizes, text scales smoothly across different screen sizes while remaining readable and consistent.

## What I Learned

During this project, I practiced:

* Creating reusable design tokens with CSS variables
* Building responsive layouts with Flexbox
* Using `clamp()` for fluid typography
* Improving code organization and maintainability
* Applying semantic HTML elements

## Links

* Solution URL: [frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS)    

## Author

* GitHub - Thiago Brandão Neves
* Frontend Mentor - [frontendmentor.io/profile/thiagoBDN](https://www.frontendmentor.io/profile/thiagoBDN)

## Acknowledgments

Challenge provided by Frontend Mentor. This project was built as part of my front-end development practice to improve responsive design and modern CSS skills.
