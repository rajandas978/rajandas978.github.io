# Rajan Das — BI & Analytics Leadership Portfolio

A responsive executive-style portfolio website built with HTML, CSS and vanilla JavaScript for GitHub Pages.

## Website
https://rajandas978.github.io

## Portfolio features
- Embedded interactive Tableau Public visualization (Customer Satisfaction Dashboard)
- Selected Tableau Public gallery links
- Two anonymized leadership case studies: BI Governance & Tableau Platform Adoption, and Enterprise Analytics Transformation

## Files
- `index.html` — portfolio content and structure
- `styles.css` — responsive visual theme
- `script.js` — mobile navigation and footer year

## Publish / update
The site is hosted from the `main` branch and repository root using GitHub Pages.
1. Commit updated files to `main`.
2. Open repository **Settings → Pages** and confirm source is **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Wait for the Pages deployment under **Actions**.
4. Visit https://rajandas978.github.io.

## Add your professional photograph
The homepage currently has a designed portrait placeholder. To use your real photograph:
1. Add a professional headshot named `rajan-profile.jpg` under `assets/`.
2. Replace the `portrait-placeholder` block in `index.html` with:
   `<img class="portrait-image" src="assets/rajan-profile.jpg" alt="Rajan Das, BI and Analytics Leader">`
3. Add CSS for `.portrait-image`: `width:100%;height:365px;object-fit:cover;object-position:center 30%;`.
4. Commit the changes.

## Public project repositories
- [BI Adoption & Governance Intelligence Engine](https://github.com/rajandas978/Bi-adoption-governance-engine)
- [TableauMind AI](https://github.com/rajandas978/TableauMind-AI-Task)
- [Tableau Admin Automation](https://github.com/rajandas978/tableau-admin-automation)
- [SQL Interview & Practice Library](https://github.com/rajandas978/sql-interview-questions)

## Accuracy and confidentiality
- Career timeline and roles are based on the professional history currently available; please review them before external use.
- The reported 70–90% report-generation-time reduction is a previously supplied career achievement for selected financial reports; retain only if you can substantiate it in an interview.
- Project descriptions summarize public repositories and portfolio work; they do not claim client deployment.
- Never publish employer-confidential data, source code, screenshots, schemas, credentials or customer information.
- Skills listed represent experience and exposure; be prepared to explain your actual depth for each.

## Local preview
Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.
