# EqualiTEA Reference-Matched Production Run Summary

Date: August 24, 2026

## Outcome

The corrected production package uses the owner-specified published page as the exact layout and styling authority:

https://carajoy.github.io/equalitea-3/EQUALITEA_COMPLETE_DESIGNER_HANDOFF_2026-08-22/EQUALITEA_PRODUCTION_HANDOFF_v1/home.html

The package restores that home.html structure and stylesheet. Only approved owner-supplied copy corrections and approved asset substitutions differ. Nothing was deployed.

## Files

- home.html is the production page.
- index.html redirects to home.html for folder-root hosting.
- styles.css is content-identical to the published reference stylesheet after normalizing line endings.
- All four locally hosted reference fonts are included under assets/fonts/.
- Production images and logos remain local under assets/production/.

## Approved differences from the published reference

- Reisha Roopchand Allen is identified as 3rd Annual EqualiTEA Co-Chair in Today’s Voices.
- Wendy Sartory Link uses the complete owner-supplied biography and title.
- Dr. Cassondra Corbin-Thaddies uses the complete owner-supplied biography.
- The full owner-supplied Norton Museum of Art logo replaces the cropped logo.
- DEX Imaging and Speak Up for Kids retain both logos with no visible combined text label or slash.
- The committee uses Edan Dela Mea and adds Marybel Coleman and Amber Schmeider.

## Layout preservation evidence

- The production stylesheet and the published reference stylesheet are identical after normalizing line endings.
- The home.html file comparison contains only the six approved copy or asset substitutions listed above.
- Section order remains Hero, Today’s Program, Today’s Voices, Featured Biographies, Modern Historical Elegance, Sponsors, Committee and Credits, and Save the Date 2027.
- Today’s Voices card order remains Ashley, Angela, Julia, Takeata, Gabrielle, Wendy, Dr. Cass, Erica, Reisha, Adrienne, and Charlee.
- No class, grid, typography, color, footer, animation, breakpoint, spacing, or responsive-style change was introduced.

## Content and asset QA

- 9 program items.
- 11 Today’s Voices cards.
- Exactly 4 Featured Biographies.
- 8 committee names.
- Adrienne Percival is spelled with an i and uses the final approved portrait.
- Gabrielle Benson, PA-C, MSPAS uses the final approved portrait and approved affiliations.
- 58 of 58 page images loaded successfully during the complete browser sweep.
- 0 broken browser images.
- 46 unique local HTML and CSS references with 0 missing files.
- 0 duplicate HTML identifiers.
- 0 browser console warnings or errors.
- All six same-page navigation targets resolve.
- 0 scripts, 0 iframes, and 0 runtime API calls.

## Desktop and mobile QA

- Desktop at 1280 by 900 matched the published reference and had no horizontal overflow.
- Phone at 390 by 844 matched the published reference.
- The published reference has inherited phone overflow: document scroll width 403 pixels against a 375 pixel client width. The corrected package has the same measurement and the same overflowing .panel__inner element.
- The inherited phone overflow was not changed because the owner locked the published layout and styling.
- The published reference does not use srcset image candidates. None were added because the correction is limited to copy and approved asset substitutions.

## Performance and burst simulation

- Critical local set: home.html, styles.css, four local fonts, and hero image total 245,098 bytes before transfer compression.
- 51 optimized production assets total 2,374,138 bytes.
- 56 of 58 image elements use lazy loading.
- 200 of 200 simultaneous home.html requests succeeded with 0 failures.
- Page burst wall time was 19,543.8 ms. Request p95 was 3,241.5 ms and maximum was 5,330.8 ms on the local test server.
- 800 of 800 critical-file requests succeeded with 0 failures for 200 simulated guests requesting four critical files.
- Critical-file burst wall time was 64,634.8 ms. Request p95 was 178.7 ms and maximum was 3,932.0 ms.
- These local results verify file integrity under the simulated request count. They do not certify the final CMS, origin, CDN, compression, or cache behavior.

## Remaining production risks

- The exact publishing host and CDN cache configuration remain unverified. Apply and verify the policy in _headers or its platform equivalent before the event.
- The published reference’s inherited phone overflow remains because correcting it would require a styling change.
- Responsive srcset candidates are not present in the published reference. Adding them would require a separate technical change outside the copy-only correction.
- A destination for the combined DEX Imaging and Speak Up for Kids logo block remains pending Chamber confirmation.
- This source folder is not a Git repository. No commit or deployment was performed.

## Deployment status

Not deployed. The reference-matched package is ready for owner and web designer review.

