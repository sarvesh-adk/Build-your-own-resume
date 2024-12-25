# Resume LaTeX Template

This repository contains a LaTeX template for creating a professional resume. The template is simple and flexible, designed for software engineers and tech professionals to showcase their qualifications and experience effectively.

## Features

- **Clean and modern layout**: The template uses a custom `resume.cls` class for a streamlined and polished design.
- **Customizable sections**: Sections like "Objective," "Education," "Experience," "Skills," and "Projects" are easily customizable for your needs.
- **Compact format**: Designed with minimal margins and optimal use of space to ensure the resume remains concise while highlighting key details.
- **Links for contact and online presence**: Includes sections to display your contact info, LinkedIn, and website links.

## Sections Included

1. **Objective**: A brief section to state your career goals or desired roles.
2. **Education**: Lists your academic qualifications and relevant coursework.
3. **Skills**: A table to list your technical and soft skills.
4. **Experience**: Describes your previous roles and achievements, with bullet points for easy readability.
5. **Projects**: Highlights relevant projects you've worked on, including descriptions and links.
6. **Extra-Curricular Activities**: Showcases your involvement in relevant side projects or contributions outside work.
7. **Leadership**: Emphasizes any leadership or administrative roles you’ve undertaken, with a focus on teamwork and impact.

## Customizing Your Resume

### Personal Information

- Edit the `\name`, `\address`, and `\email` commands to reflect your personal information. You can also add additional fields like your portfolio or GitHub URL if necessary.
  
### Sections

- Each section (`OBJECTIVE`, `EDUCATION`, `EXPERIENCE`, `SKILLS`, `PROJECTS`, `Extra-Curricular Activities`, `Leadership`) can be easily modified by adding/removing items, changing the formatting, or adjusting bullet points.
- For the `PROJECTS` section, you can add a link to external projects or provide a detailed description of what the project achieved.

### Technical Skills

- In the `SKILLS` section, you can add or remove technical skills and soft skills according to your experience.

### Experience and Projects

- In the `EXPERIENCE` and `PROJECTS` sections, replace the placeholders with your own job roles, achievements, and project details. Quantify your successes to make them stand out!

## Compilation Instructions

1. Make sure you have LaTeX installed on your system (e.g., using TeX Live, MiKTeX, or Overleaf).
2. Save the file as `resume.tex`.
3. Run the following command to compile the LaTeX file into a PDF:
   ```bash
   pdflatex resume.tex
