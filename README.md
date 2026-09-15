# CHRISTISEN ZEMBE PROFILE

This project is a simple student profile website created for the Software Engineering and Web Technologies assignment. The page includes a clean academic layout, semantic HTML structure, and a minimal style that matches the assignment requirements.

## Project Purpose

The website presents a student profile with:

- a profile header and navigation
- academic and personal details
- a personal statement under the About section
- skills and contact information
- simple form styling with semantic HTML

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

## Peer Review Accessibility Feedback

During the peer review on Thursday, the reviewer identified a visibility and colour-contrast issue with the "Software Engineering | Web Technologies" program label in the red header. The text was visually subdued because it inherited a reduced opacity, which made it less clear to read.

The fix was applied in `styles.css` by setting `.program-tag` to solid white (`color: #fff`) and removing the opacity reduction. This makes the label clearer against the header background and provides evidence that the peer-review feedback was acted on.

## Assignment Coverage

This commit is aligned with the assignment requirements and includes:

### Part A: Semantic HTML5 structure

- HTML5 document skeleton with title and meta description
- Semantic header, nav, main, section, article, figure, address, and footer elements
- Properly nested heading levels and section navigation

### Part B: Website structure

- Student name and tagline in the header
- Profile, About, Academic Information, Skills, and Contact sections
- Contact form with text, telephone, email, and textarea fields
- Labels and native validation attributes on every form control

### Part C: Semantic HTML

- AI prompt, raw output, final edited version, and reflection are recorded above
- The About section copy was critically revised before being used

### Part D: Styling and layout

- Meaningful accessible labels for the initials figure and form fields
- Readable red-and-white colour contrast
- Responsive layout for smaller screens

### Part E: Version control

- Incremental commits document the profile, personal statement, visibility fix, final message, merge, and documentation updates
- The finished page is pushed to the public GitHub repository

### Part F: Code quality

- Consistently indented HTML and CSS with no placeholder text
- The page uses native HTML5 validation without JavaScript

## Files Included

- `profile.html` – main profile page
- `styles.css` – styling for the assignment website

## How to Run

Open `profile.html` in a browser to view the website.
