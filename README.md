# homepage# Responsive Homepage

A responsive portfolio-style homepage built with **HTML and CSS** as part of **The Odin Project Advanced HTML and CSS course**.

The project focuses on responsive design, semantic HTML, accessibility, CSS Grid, Flexbox, and adapting a layout across desktop, tablet, and mobile screen sizes.

## Features

* Responsive desktop, tablet, and mobile layouts
* Hero/About section with overlapping portrait and content card
* Responsive project grid using CSS Grid
* Project cards with source and live-site links
* Contact section with responsive image layout
* Social media links and contact information
* Responsive images using `object-fit`
* Keyboard-accessible navigation
* Semantic heading structure
* Mobile-friendly layout down to small screen sizes

## Built With

* HTML5
* CSS3
* CSS Grid
* Flexbox
* Media Queries
* CSS Custom Properties
* Google Fonts

## Responsive Design

The layout adapts across three general screen sizes:

### Desktop

* Portrait and About section displayed side-by-side
* Projects automatically arranged across multiple columns
* Contact information and image displayed side-by-side

### Tablet

* Hero layout becomes more compact
* Project grid reduces the number of columns as available space decreases
* Contact section remains side-by-side with adjusted proportions and spacing

### Mobile

* Hero section stacks vertically
* Projects display in a single column
* Contact section stacks vertically
* Spacing and typography are adjusted for smaller screens

The project grid uses:

```css
grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
```

which allows the number of columns to adapt automatically to the available space and number of projects.

## Accessibility

Accessibility considerations include:

* Semantic HTML elements and heading hierarchy
* Descriptive alternative text where appropriate
* Keyboard-accessible links
* Visible keyboard focus
* Responsive content that remains usable without horizontal scrolling
* Meaningful link descriptions
* Color contrast considerations
* Decorative images hidden from assistive technologies where appropriate

## What I Learned

This project gave me practice with:

* Designing layouts for multiple viewport sizes
* Choosing responsive breakpoints
* Using CSS Grid and Flexbox together
* Creating layouts that adapt without relying heavily on fixed dimensions
* Using `aspect-ratio` and `object-fit` for responsive images
* Layering elements with positioning and `z-index`
* Creating angled backgrounds using `clip-path`
* Maintaining visual hierarchy across different screen sizes
* Considering keyboard navigation and accessibility while styling a page

One of the main challenges was recreating the hero section across desktop, tablet, and mobile layouts while keeping the portrait, background, and About section visually balanced.

## Running Locally

Clone the repository:

```bash
git clone git@github.com:RT1811/homepage.git
```

Enter the project directory:

```bash
cd homepage
```

Then open `index.html` in your browser.

No JavaScript or build tools are required.

## Project Context

This project was completed as part of **The Odin Project — Advanced HTML and CSS** curriculum.

The goal was to reproduce a provided design while making the page responsive across desktop, tablet, and mobile devices.

## Author

**Ritwick Thakur**

GitHub: `RT1811`
