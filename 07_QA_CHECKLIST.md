# 07 — QA Checklist

## Content
- [ ] Event name is correct.
- [ ] August 26, 2026 is correct.
- [ ] The Ben, West Palm Beach is correct.
- [ ] Theme line is correct.
- [ ] Program order matches the approved Chamber program.
- [ ] Adrienne Percival = Closing Reflection.
- [ ] Charlee Nolan = Annual Hat Contest.
- [ ] Women’s Foundation spelling is used.
- [ ] All 11 participants are represented.
- [ ] Only four full biographies appear.
- [ ] Wendy Sartory Link and Dr. Cassondra Corbin-Thaddies use the complete owner-supplied August 24 biographies.
- [ ] Reisha Roopchand Allen is identified as a 3rd Annual EqualiTEA Co-Chair in Today’s Voices.
- [ ] Erica Grant uses supplied 2026 headshot and supplied bio.
- [ ] Erica Grant pronouns are preserved from supplied bio.
- [ ] The She’s Online Group appears as Program Design credit, not sponsor.

## Navigation
- [ ] Program anchor works.
- [ ] Speakers anchor works.
- [ ] Sponsors anchor works.
- [ ] About EqualiTEA anchor works.
- [ ] View Featured Biographies jumps to biography section.
- [ ] No dead buttons.
- [ ] No invented external links.

## Sponsors
- [ ] Sponsor names match approved program.
- [ ] Sponsor levels match approved program.
- [ ] Canva classification does not override approved program.
- [ ] Every clickable sponsor logo uses a verified official destination.
- [ ] Unverified sponsor links remain non-clickable.
- [ ] Media Partner and Historic Exhibit Partner are included.
- [ ] Vendors are included as approved.
- [ ] DEX Imaging and Speak Up for Kids display as logos only, with no visible combined text label or slash.
- [ ] The exact owner-supplied full black Norton Museum of Art logo is installed from the optimized production asset.

## Visual
- [ ] Rendered desktop and mobile layout matches the exact published home.html implementation reference.
- [ ] No card order, section order, class name, grid, spacing, typography, color, footer, or responsive-rule change was introduced.
- [ ] Production styles.css matches the published implementation reference with no styling changes.
- [ ] Desktop visually follows approved layout.
- [ ] Mobile visually follows approved layout.
- [ ] Panel has stronger visual emphasis.
- [ ] Speaker images are correctly matched.
- [ ] Gabrielle’s final approved headshot is correctly matched.
- [ ] Adrienne Percival’s final approved headshot is correctly matched.
- [ ] The She’s Online Group logo is exact, not recreated.
- [ ] Suffrage colors retain intended meaning.
- [ ] 2027 Save the Date has a purposeful closing treatment.
- [ ] Committee includes Edan Dela Mea, Marybel Coleman, and Amber Schmeider using the owner-supplied spellings.

## Mobile
- [ ] No horizontal overflow.
- [ ] No pinch-to-zoom needed.
- [ ] Type is readable at normal scale.
- [ ] Tap targets are comfortable.
- [ ] Sponsor logos remain legible.
- [ ] Headshots crop well on narrow screens.
- [ ] Page feels fast on cellular connection.

## Performance and burst capacity
- [ ] Page remains static-first and does not require JavaScript for core content or navigation.
- [ ] No unnecessary third-party scripts, embeds, trackers, animations, or runtime API calls are present.
- [ ] Production images are compressed and smaller than oversized source originals.
- [ ] Responsive image candidates and sizing rules are present where they reduce delivery weight.
- [ ] Below-the-fold images use lazy loading.
- [ ] Mobile page weight, rendering, overflow, console health, and image loading are tested.
- [ ] A local or staging burst simulation appropriate for approximately 200 near-simultaneous guests completes without failed responses.
- [ ] HTML, CSS, and asset caching behavior is verified on the actual publishing host or CDN.
- [ ] Any CMS, host, cache, or server limitation is documented before final publication.

## Accessibility
- [ ] Heading hierarchy is semantic.
- [ ] Alt text is accurate.
- [ ] Keyboard navigation works.
- [ ] Focus is visible.
- [ ] Contrast passes.
- [ ] Reduced-motion preference is respected if motion exists.

## Final
- [ ] Compare rendered page side-by-side with `EQUALITEA_PROGRAM_LAYOUT.png`.
- [ ] Verify all names, titles, organizations, roles and order.
- [ ] Test every external URL.
- [ ] Test the QR destination.
- [ ] Record mobile performance and approximately 200-user burst-test results in `PRODUCTION_RUN_SUMMARY.md`.
- [ ] Obtain approval before deployment.

## Reference-matched validation result — August 24, 2026

Passed:

- [x] Published home.html structure and Today’s Voices order preserved.
- [x] Production styles.css matches the published reference after line-ending normalization.
- [x] Only approved copy and approved asset substitutions differ from the published reference.
- [x] 11 voice cards and exactly 4 full biographies.
- [x] 58 of 58 browser images loaded with 0 broken images.
- [x] 46 unique local HTML and CSS references with 0 missing files.
- [x] 0 duplicate IDs and 0 browser console warnings or errors.
- [x] Desktop rendering at 1280 by 900.
- [x] Phone rendering at 390 by 844.
- [x] 200 of 200 simultaneous page requests completed successfully.
- [x] 800 of 800 critical-file requests completed successfully.

Open before publication:

- [ ] The exact published reference has inherited phone overflow of 403 pixels against a 375 pixel client width from .panel__inner. The corrected package preserves it because styling changes are prohibited.
- [ ] The exact published reference does not include srcset candidates. None were added under the copy-only correction.
- [ ] Verify caching, compression, and burst behavior on the actual CMS, host, and CDN.
- [ ] Confirm the destination for the combined DEX Imaging and Speak Up for Kids logo block.
