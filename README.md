# TaskFlow — Responsive Landing Page

A modern, minimal landing page concept for TaskFlow, a fictional productivity and project-management platform. Built as an internship warm-up task using HTML, CSS, and a small amount of vanilla JavaScript.

## Features

- Responsive layouts for mobile, tablet, and desktop.
- Mobile navigation menu with accessible expanded/collapsed state.
- Hero section with a dashboard preview.
- Product features, workflow steps, testimonial, and call-to-action sections.
- Responsive images and layout constraints to prevent horizontal overflow.
- Semantic HTML, descriptive page metadata, and reduced-motion support.

## Tech stack

- HTML5
- CSS3 (Grid, Flexbox, media queries, custom properties)
- Vanilla JavaScript

## Run locally

No build tools or dependencies are required.

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a browser.

For a local development server, you can also use the VS Code **Live Server** extension.

## Responsive testing

Test the page using browser developer tools at these widths:

- 375px — required mobile width
- 768px — tablet
- 1440px — desktop

Check that the navigation works on mobile, all content remains readable, images stay within their containers, and no horizontal scrollbar appears.

## Design decisions

- A restrained lavender, warm-white, and deep-navy palette gives the product a calm, premium feel.
- The dashboard preview communicates the product quickly without requiring a separate screenshot asset.
- Content is organized into short sections so visitors can scan the value proposition.
- The layout uses CSS Grid and Flexbox with responsive breakpoints rather than fixed page widths.

## Notes

TaskFlow is a fictional product created for a front-end practice assignment. The testimonial, team names, and product metrics are illustrative. Google Fonts and Unsplash profile images are loaded from external URLs, so an internet connection is needed for those assets. The page remains usable if those external assets are unavailable.
