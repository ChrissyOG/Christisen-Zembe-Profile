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

Note:
The first AI-generated personal statement was a bit formal and slightly unnatural in tone. The final version used in the profile was refined to sound more natural, friendly, and personal while keeping the original meaning and intent intact. This revision is simply an improvement of the same idea, not a different message.

## Peer Review Accessibility Feedback

During the peer review on Thursday, the reviewer identified a visibility and colour-contrast issue with the "Software Engineering | Web Technologies" program label in the red header. The text was visually subdued because it inherited a reduced opacity, which made it less clear to read.

The fix was applied in `styles.css` by setting `.program-tag` to solid white (`color: #fff`) and removing the opacity reduction. This makes the label clearer against the header background and provides evidence that the peer-review feedback was acted on.

## Assignment Coverage
This commit is aligned with the assignment requirements and includes:

### Part A: Student profile content
- Student name
- Student ID: 250585
- Program: Software Engineering
- Course: Web Technologies
- Academic profile information

### Part B: Website structure
- Header and navigation
- Profile section
- About section
- Skills section
- Contact section

### Part C: Semantic HTML
- Use of semantic elements such as header, nav, main, section, article, figure, and address
- Meaningful section headings and accessible structure
- Clear content organisation for the website

### Part D: Styling and layout
- Clean academic design
- Simple theme with a professional red-and-white colour scheme
- Proper spacing, layout consistency, and readable typography
- Responsive layout for smaller screens

## Files Included
- `profile.html` – main profile page
- `styles.css` – styling for the assignment website

## How to Run
Open `profile.html` in a browser to view the website.
