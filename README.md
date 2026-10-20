# Shortlist Resume Builder

A step-by-step resume builder that asks you questions one section at a time and produces an ATS-friendly resume. It's a single HTML file with no build step, no server and no sign-up.

## What it does

- **Guided questions in 8 steps:** Target job, Contact, Experience, Skills, Education, Certifications, Summary, Check & export.
- **Live preview:** a letter-size resume updates as you type.
- **ATS-safe layout:** one column, standard section headings, contact details as plain text, and no tables, icons or images.
- **Job-post keyword match:** paste a job description to see which of its keywords your resume covers and which are missing. On the Skills step you can tap a missing keyword to add it.
- **Feedback on achievement lines:** flags lines without numbers, weak openers such as "Responsible for…", and lines that run too long.
- **ATS score with a checklist:** every failed item links back to the step that fixes it.
- **Summary draft:** writes a first draft of your summary from your answers.
- **Export:**
  - Text-based PDF, which an ATS can read line by line
  - Word (.doc)
  - Plain text
  - Copy to clipboard

## Use it

Open `index.html` in any modern browser. Your answers are saved in that browser's local storage and never leave your device.

To host it, enable **GitHub Pages** for this repository (Settings → Pages → Deploy from branch → `main` / root). The app will then be live at `https://<your-username>.github.io/shortlist-resume-builder/`.

The PDF export loads [jsPDF](https://github.com/parallax/jsPDF) 2.5.1 from cdnjs, so it needs an internet connection. Everything else works offline.

## Tips for an ATS-friendly resume

- Tailor one resume per application and mirror the exact job title and tool names from the post, as long as they're true for you.
- Write each achievement as an action verb, then what you did, then a measurable result. Aim to put a number in at least 60% of your lines.
- Use month and year for dates, written the same way everywhere (e.g. `Mar 2022 – Present`).
- Send the PDF unless the job post asks for Word.
