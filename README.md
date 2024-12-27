# Resume LaTeX Template

This repository contains a LaTeX template for creating a professional resume, designed for software engineers and tech professionals to effectively showcase their qualifications and experience.

## Features

- **Clean and modern layout**: Uses a custom `resume.cls` class for a streamlined, polished design.
- **Customizable sections**: Easily editable sections for "Objective," "Education," "Experience," "Skills," "Projects," and more.
- **Compact format**: Optimized layout to ensure conciseness without sacrificing detail.
- **Contact and online presence links**: Sections to display your contact info, LinkedIn, and website links.

## Sections Included

1. **Objective**: A brief statement about your career goals or desired roles.
2. **Education**: Lists academic qualifications and relevant coursework.
3. **Skills**: A table to showcase both technical and soft skills.
4. **Experience**: Describes previous job roles and achievements.
5. **Projects**: Highlights projects you've worked on with descriptions and links.
6. **Extra-Curricular Activities**: Showcases relevant side projects or non-work-related contributions.
7. **Leadership**: Emphasizes leadership roles and team impact.

## Customizing Your Resume

### Personal Information

- Edit the `\name`, `\address`, and `\email` commands to reflect your personal information. You can also add additional fields such as GitHub or portfolio URLs if needed.

### Sections

- Each section (`OBJECTIVE`, `EDUCATION`, `EXPERIENCE`, `SKILLS`, `PROJECTS`, `Extra-Curricular Activities`, `Leadership`) can be customized by adding/removing items, changing formatting, or adjusting bullet points.
- The `PROJECTS` section allows you to add links or provide detailed descriptions of the projects you've worked on.

### Technical Skills

- In the `SKILLS` section, you can modify the list of technical and soft skills based on your experience.

### Experience and Projects

- Replace placeholders in the `EXPERIENCE` and `PROJECTS` sections with your own job details, accomplishments, and project highlights. Quantifying achievements helps them stand out!

## Compilation Instructions

1. Ensure LaTeX is installed on your system (e.g., TeX Live, MiKTeX, or Overleaf).
2. Save the file as `resume.tex`.
3. Compile the LaTeX file into a PDF by running the following command:
   ```bash
   pdflatex resume.tex
