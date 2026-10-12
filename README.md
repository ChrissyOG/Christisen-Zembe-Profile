# CHRISTISEN ZEMBE PROFILE

This project is a responsive student profile website created for the Software Engineering and Web Technologies assignment. The page keeps the original semantic HTML5 structure from Assignment 1 and adds a stronger visual system using CSS, Flexbox, Grid, and Tailwind utilities.

## Project Purpose

The website presents a student profile with:

- a profile header and navigation
- academic and personal details
- a personal statement under the About section
- skills organised in a responsive card grid
- contact details and a styled contact form
- accessibility-friendly, mobile-first styling

## Tailwind and CSS Split

This version intentionally mixes Tailwind utilities with custom CSS:

- Tailwind is used for the main navigation and the contact form layout, including at least one responsive variant (`sm:` and `md:`) in the markup.
- Custom CSS handles the global page design, colour palette, spacing, box model choices, and the grid/flex layouts that are central to the assignment requirements.
- This separation keeps the HTML readable while preserving a consistent, purposeful design system rather than duplicating styles across files.

## Prompt Log

### Strong prompt used for the About section

Prompt:
"Create a simple and professional personal statement for a Software Engineering student studying Web Technologies. The paragraph should be one short academic paragraph, suitable for a student profile website. It must clearly express the student’s interest in web development, digital problem-solving, and learning modern technology. Keep the tone professional, concise, and easy to read. The About link should lead to only the personal statement section, not a full biography or multiple sections."

Result:
"I am a simple and motivated student studying Software Engineering, with a strong interest in web development and digital problem-solving. I enjoy learning how modern websites are built and how technology can be used to solve real-world challenges."

Final edited version used on the page:
"I am a motivated Software Engineering student with a growing interest in web development, problem-solving, and building practical digital solutions. I enjoy learning how websites and technologies work, and I am always looking for ways to improve my skills while applying what I learn in a real-world setting."

Reflection:
The raw response sounded slightly formal and did not feel personal enough. I kept its main ideas about web development and problem-solving, but made the wording friendlier and connected it more clearly to practical learning.

## Assignment Coverage

### Part A — CSS3 Fundamentals & Box Model

- Semantic HTML5 structure from Assignment 1 remains intact.
- Typography, spacing, and colour system were designed for clear visual hierarchy.
- Styling is applied through a linked external stylesheet and selected Tailwind classes instead of inline styles.
- Margin, padding, borders, and box sizing were intentionally adjusted rather than relying on browser defaults.

### Part B — Flexbox Layout

- The navigation bar uses Flexbox for alignment, wrapping, spacing, and centring.
- The contact form field groups also use Flexbox for consistent alignment and responsive stacking.
- Multiple Flexbox properties are used, including `display: flex`, `flex-wrap`, `justify-content`, and `align-items`.

### Part C — CSS Grid Layout

- The page uses CSS Grid for the main content container and the skills section card layout.
- Grid items use meaningful spacing and responsive columns, including `repeat()` and `minmax()` patterns.
- The skills grid demonstrates a real grid layout instead of a simple single-column list.

### Part D — Responsive Design & Media Queries

- The stylesheet is built mobile-first, with wider layouts added through `min-width` media queries.
- Custom media queries were written for tablet and desktop breakpoints.
- The layout is designed to stay clean at approximately 375px, 768px, and 1280px.
- Content reflows without horizontal scrolling, overlapping text, or broken navigation.

### Part E — Tailwind Utility-First Styling

- The header navigation is styled using Tailwind utility classes.
- The contact form layout uses Tailwind utilities for spacing and responsive column changes.
- Responsive variants are included to adjust spacing and layout at larger breakpoints.

### Part F — Testing & Code Quality

- The page was reviewed and adjusted for all three required breakpoints in the responsive design plan.
- The markup is semantic, consistent, and free of placeholder or lorem text.
- No console errors were introduced during the final layout updates.

## Testing Notes

Testing checklist completed for the required responsive breakpoints:

- Mobile: approximately 375px
- Tablet: approximately 768px
- Desktop: approximately 1280px

The layout was checked for overflow, navigation stability, and text readability across these widths.

## Files Included

- `profile.html` – main profile page and Tailwind-enabled markup
- `styles.css` – custom responsive styling and layout rules

## How to Run

Open `profile.html` in a browser to view the website.
