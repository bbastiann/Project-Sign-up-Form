# Project: Sign-up Form

This is a responsive and validated Sign-up Form landing page built as part of the Intermediate HTML and CSS path from [The Odin Project](https://www.theodinproject.com/). 

The goal of this project was to practice form structure, semantic HTML, advanced CSS layouts (Flexbox), and native client-side form validation.

## Features

- **Semantic HTML5:** Structured with accessibility in mind, properly linking all `<label>` elements to their respective `<input>` fields.
- **Custom Native Validation:** - The phone number input utilizes `type="tel"` combined with a strict Regex `pattern` tailored for **Chilean mobile formats** (`9XXXXXXXX`).
  - Password fields enforce a security constraint using `minlength="8"`.
- **User-Centric UX/UI:** Applied the `:user-invalid` CSS pseudo-class to dynamically alert users with clear visual feedback (red borders and shadows) only after they interact with a field and leave it invalid.
- **Responsive Layout:** Built using Flexbox to separate the decorative left sidebar from the dynamic right-side form section.

## Technologies Used

- HTML5
- CSS3 (Flexbox, Custom Fonts, Pseudo-classes)
- Git & GitHub

## What I Learned

During this project, I deepened my understanding of how browsers handle native form validation without relying heavily on JavaScript scripts from the start. Key takeaways include:
1. Shifting from `type="number"` to `type="tel"` to eliminate native browser spin buttons (arrows) and improve mobile keyboard behavior.
2. Triggering UX-friendly validation states via CSS using `:user-invalid` instead of `:invalid`, which prevents fields from looking broken before the user even finishes typing.

## How to Run

1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/project-sign-up-form.git](https://github.com/YOUR_USERNAME/project-sign-up-form.git)
