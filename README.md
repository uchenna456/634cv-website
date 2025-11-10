# Uchenna CV Website (Single Page)

A responsive, accessible one‑page CV website built with **Bootstrap 5** and **Google Fonts**.

## Deploy to GitHub Pages
1. Create a new public repo on GitHub called `cv-website` (or any name).
2. In VS Code, run:
- Initialize git (`git init`) and commit all files.
- Add remote: `git remote add origin https://github.com/<YOUR-USERNAME>/<REPO>.git`
- Push: `git branch -M main` then `git push -u origin main`
3. On GitHub, go to **Settings → Pages**:
- **Source**: `Deploy from a branch`
- **Branch**: `main` and **/ (root)**, then **Save**
4. Wait a minute; your site will be live at `https://<YOUR-USERNAME>.github.io/<REPO>/`.


## How each of the 5+ sections uses a different design element
- **Intro/Hero**: full‑bleed banner with CTA buttons and circular photo.
- **About**: two‑column layout + statistic cards (different image/text arrangement).
- **Skills**: Bootstrap **progress bars** and **badges**.
- **Experience & Education**: custom **vertical timeline** + **table** for education and **list‑group** for certifications.
- **Projects**: Bootstrap **cards** with badges.
- **Contact**: responsive **form** + list‑group of details on dark background.


## Accessibility Checklist
- Semantic landmarks: `<nav>`, `<header>`, `<section>`, `<footer>`.
- Proper heading order and labels; form inputs have `<label>`s.
- Images include `alt` attributes.
- Color contrast friendly on dark sections.


## Responsiveness
- Built on Bootstrap grid; additional small media‑query tweaks in `styles.css`.


## Where to change content
- Text, dates, and lists live inside the relevant section in `index.html`.
- Colors/spacing in `styles.css` (keep brand color in the `:root` block).


## What to submit (per course sheet)
- **Push final code** to the repo before the deadline.
- Ensure **GitHub Pages** is turned on and working.
- Complete the course **Final Project Submission Sheet** with your repo + pages links and short comments.
