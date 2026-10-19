# Md. Shihab Uddin — Professional E-Portfolio

A responsive, dark modern portfolio built with plain HTML, CSS, and JavaScript. No build step or package manager is required.

## Included
- Responsive homepage and navigation
- About and education
- Honors and awards
- Research publications with expandable details
- Eight CV-based project cards and category filters
- Research experience and leadership
- Technical skills and contact links
- CV PDF in `assets/Md_Shihab_Uddin.pdf`

## Run locally
Open `index.html` in a browser. For best results, use a local server:
- VS Code: install/use Live Server, then open the project folder
- Python: `python -m http.server 8000` from this directory, then visit `http://localhost:8000`

## Deploy to GitHub Pages
1. Create a new GitHub repository (for example, `shihab-portfolio`).
2. Upload the contents of this folder to the repository root.
3. In repository Settings → Pages, select deployment from the `main` branch and `/ (root)`.
4. Wait for the published URL and test it on desktop and mobile.

## Deploy to Vercel
1. Push this folder to a GitHub repository.
2. Import that repository into Vercel.
3. Choose the static site/default settings; no build command is needed.
4. Deploy.

## Before publishing — important checklist
- Add the actual repository/demo links for projects. The CV provided for this build did not include usable repository URLs, so those links have deliberately not been invented.
- Add official paper/proceedings/DOI URLs and verify publication and indexing status.
- Confirm whether each listed research item is published, accepted, under review, or ongoing; this website uses cautious language where the CV did not specify.
- Add a professional headshot only if desired.
- Confirm contact details and CV are current.
- The portfolio uses a Google Fonts CDN for Manrope and DM Mono; system fonts will be used if it is unavailable.

## Files
- `index.html` — page content
- `styles.css` — theme, layout, responsive styles
- `script.js` — navigation, publication accordions, project filters
- `assets/Md_Shihab_Uddin.pdf` — original CV supplied for this task
