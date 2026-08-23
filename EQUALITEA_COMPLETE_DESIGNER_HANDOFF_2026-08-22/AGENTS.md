# Repository Guidelines

## Project Structure and Source of Truth

The working site is under `EQUALITEA_PRODUCTION_HANDOFF_v1/`. `index.html` redirects visitors to `home.html`, which contains the current program page. Shared styling lives in `styles.css`; deployable images and fonts live in `assets/production/` and `assets/fonts/`. Keep `source-documents/` and `assets/reference-layout/` unchanged as provenance and visual references.

Before editing content, read `00_READ_ME_FIRST.md`, then follow the authority order defined there. `01_LOCKED_DECISIONS.md` controls settled names, roles, sequence, sponsor treatment, and design decisions. Never copy superseded wording from historical source files into the production page.

## Local Preview and Validation

This is a framework neutral static site. It has no package manager, build step, automated test suite, or runtime dependency. From the handoff directory, preview it with:

```powershell
cd EQUALITEA_PRODUCTION_HANDOFF_v1
python -m http.server 8000
```

Open `http://localhost:8000/` and confirm the redirect and rendered page. Before committing, run `git diff --check`, then complete the relevant checks in `07_QA_CHECKLIST.md`. Test phone and desktop layouts, keyboard focus, anchors, image loading, console output, and horizontal overflow. Verify every changed external link and QR destination. Hosting cache and 200 guest burst requirements must be validated in an authorized staging environment.

## Coding Style and Assets

Preserve the existing semantic HTML, accessible labels, two space HTML indentation, CSS custom properties, and component style class names such as `.voice-card` and `.sponsor-group`. Keep the page usable without JavaScript. Use optimized local assets, responsive `srcset` values where useful, explicit image dimensions, descriptive alt text, and lazy loading below the fold. Do not add frameworks, trackers, embeds, external fonts, or production dependencies without approval.

## Commits and Pull Requests

History favors brief summaries such as `Fix missing newline at end of index.html` and `Update README.md`. Use a concise imperative subject that names the affected area. Keep each commit focused. Pull requests should explain the content or layout change, identify the controlling source file, list validation performed, and include desktop and phone screenshots for visual changes. Link the issue or owner request when available. Do not deploy, rewrite locked copy, or replace approved assets without explicit approval.
