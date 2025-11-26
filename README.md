# Admin Dashboard

This is a responsive admin dashboard layout built using CSS Grid and Flexbox. This project was created as part of The Odin Project's Intermediate HTML and CSS curriculum. The primary goal was to use advanced Grid properties to build a complex, multi-section layout without relying on frameworks like Bootstrap.

---

## Features
* **Advanced Grid Layout**: A robust CSS Grid structure (`grid-template-areas` and `auto-fit`) that manages a Sidebar, Header, and Main Content area.
* **Responsive Sidebar**: A sticky sidebar navigation that stays in place while the user scrolls the main content.
* **Auto-Responsive Cards**: The "Your Projects" section uses `repeat(auto-fit, minmax())` to automatically adjust the number of columns based on screen width.
* **Semantic HTML**: The structure uses semantic tags like `<header>`, `<main>`, and `<aside>` for better accessibility and SEO.
* **Real-time Avatar Generation**: Integrated the DiceBear API to generate unique, consistent user avatars for the "Trending" section.
* **Modern UI Styling**: Features a clean design with soft box-shadows, rounded corners, and subtle hover effects for interactivity.
* **Accessibility**: Includes `aria-label` attributes on inputs and proper semantic structure for screen readers.

---

## What I Learned
This project was the capstone for the Intermediate HTML/CSS course, bringing together everything I've learned about layout.

Key takeaways include:
* **Grid vs. Flexbox**: This project clarified exactly when to use Grid (2D page layout, card grids) versus Flexbox (1D alignment of icons and text).
* **Grid Template Rows**: I learned how to solve the "whitespace" issue by using `grid-template-rows: auto 1fr` and `align-content: start`. This ensures that content pushes to the top rather than stretching to fill the page height.
* **Image Handling**: I learned how to use `object-fit: cover` to ensure that user avatars remain perfect circles without distortion, regardless of the original image dimensions.
* **CSS Variables**: I used CSS variables (`:root`) to manage standard colors, spacing, and shadows, making the codebase easier to maintain and update.

---

## Acknowledgements
* This project is based on the [Admin Dashboard assignment](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard) from The Odin Project.
* Icons provided by [Material Design Icons](https://pictogrammers.com/library/mdi/).
* User avatars generated via the [DiceBear API](https://www.dicebear.com/).
* Fonts used: 'Roboto' via Google Fonts (hosted locally).