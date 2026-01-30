# Frontend Mentor - Bento grid solution

This is my solution to the **Bento grid** challenge on Frontend Mentor. The goal of the project is to build a responsive “bento-style” layout that rearranges cleanly across screen sizes.

## Overview

### The challenge
Users should be able to:
- View the optimal layout for the interface depending on their device's screen size

### Built with
- Semantic HTML5
- Tailwind CSS (CDN)
- CSS Grid + Flexbox utilities
- Mobile-first layout adjustments 

## My approach + customizations
I built the layout using **CSS Grid** for the overall bento structure (rows/columns), then used **Flexbox** inside individual cards for aligning text and images. I used Tailwind’s utility classes to quickly style spacing, typography, and backgrounds using the HSL colors from the challenge.

Customizations I made:
- Used Tailwind CDN instead of a full Tailwind build setup to keep the project simple
- Applied rounded corners and spacing utilities for consistent card styling
- Used grid spans (row-span/col-span) to shape the bento layout

## Challenges faced + how I solved them
- **Grid placement:** Getting the cards to sit in the correct rows/columns took trial and error. I adjusted `row-start`, `row-end`, `col-start`, and `col-end` until the layout matched the design.
- **Spacing consistency:** Some cards felt “off” due to different image sizes. I fixed this by adding consistent gaps, padding, and controlled image widths/heights.
- **Responsiveness:** The layout initially worked best on desktop. I would improve it by adding responsive Tailwind classes (like `md:` and `lg:`) to restructure the grid on smaller screens.

## Links
- Solution URL: (add your Frontend Mentor solution link)
- Live Site URL: (add your deployed link)

## Author
- Frontend Mentor: [@sntungane](https://www.frontendmentor.io/profile/sntungane)
- GitHub: [@Sntungane](https://github.com/Sntungane)

## Reflection (100–200 words)
One of the biggest challenges in this project was getting the bento grid layout to match the design without items overlapping or feeling uneven. I started by building the main layout using CSS Grid and then placed each card using row and column spans. When things didn’t line up, I fixed it by adjusting `row-start`, `row-end`, and column spans until everything flowed correctly. Another challenge was spacing and image sizing—some images made certain cards taller than others and other card even more bigger. I handled that by adding consistent gaps and padding and limiting image height/width where needed. If I had more time, I would improve the mobile layout by adding more responsive Tailwind breakpoints (`sm`, `md`, `lg`) and creating a cleaner stacking order for smaller screens. I’d also refactor repeated styling into reusable Tailwind patterns for consistency.
