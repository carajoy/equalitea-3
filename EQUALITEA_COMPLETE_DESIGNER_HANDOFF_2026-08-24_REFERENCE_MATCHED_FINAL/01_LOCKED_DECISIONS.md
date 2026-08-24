# 01 — Locked Decisions

## Event
- Event: **3rd Annual EqualiTEA**
- Theme line: **Honoring the Past. Leading Today. Inspiring Tomorrow.**
- Event date: **August 26, 2026**
- Event location: **The Ben, West Palm Beach**
- Existing destination: the current 3rd Annual EqualiTEA webpage should become the event-day digital program.
- Do not create a separate PDF-based program as the primary event-day experience.

## Page order
1. Hero
2. Today’s Program
3. Today’s Voices
4. Featured Biographies
5. Modern Historical Elegance
6. Sponsors
7. Committee & Credits
8. Save the Date 2027

## Navigation
- Program → same-page anchor
- Speakers → same-page anchor
- Sponsors → same-page anchor
- About EqualiTEA → same-page anchor
- View Featured Biographies → same-page jump to biography section
- Do not create external links simply because an element looks clickable.

## Biography scope
Exactly four women receive full biographies:
1. Angela Manfredi
2. Wendy Sartory Link
3. Dr. Cassondra Corbin-Thaddies
4. Erica Grant

Do not create full biographies for the other participants.

## Name / organization correction
Use **Women’s Foundation** for Takeata King Pang in the event display. This is the approved correction and overrides the older source wording “Woman’s Foundation.”

## Speaker-photo status
- Use real, verified headshots where available.
- Gabrielle Benson, PA-C, MSPAS: use the user-supplied final approved headshot in `assets/production/headshots/Gabrielle_Benson_User_Provided.jpg`.
- Adrienne Percival: use the user-supplied final approved headshot in `assets/production/headshots/Adrienne_Percival_User_Provided.jpg`.
- Never substitute a generic AI-generated woman for either person.

## Erica Grant
Use the supplied **Erica Grant 2026** headshot and supplied biography. Do not use the older Erica image if the 2026 image is available.

## The She’s Online Group
- Program design credit belongs in **Committee & Credits**.
- Use the exact supplied 2026 The She’s Online Group logo.
- Treat it as a **production/design credit**, not as an event sponsor.
- Do not recreate, redraw, typeset, or approximate the logo.

## Sponsors
- The approved event program is the source of truth for sponsor categories and names.
- Canva is an asset source for logos and visual reference. If Canva classification conflicts with the approved program, the approved program wins.
- Current instruction: sponsor logos should link to verified official websites.
- Older notes saying sponsor logos do not need links are superseded.
- Do not invent a sponsor URL. Verify every external destination before publication.

## Sequence correction
Adrienne Percival gives the **Closing Reflection**.
Charlee Nolan leads the **Annual Hat Contest**.
Keep that order.

## Owner revisions — August 24, 2026
- In Today’s Voices, identify Reisha Roopchand Allen prominently as a **3rd Annual EqualiTEA Co-Chair** without changing the approved card order or layout.
- Replace the shortened Wendy Sartory Link and Dr. Cassondra Corbin-Thaddies biography copy with the complete owner-supplied versions in `03_BIOGRAPHIES.md`.
- Display the DEX Imaging and Speak Up for Kids logos without a visible combined text label or slash.
- Add Edan Dela Mea, Marybel Coleman, and Amber Schmeider to the EqualiTEA Committee list using these spellings.
- Use the owner-supplied full black Norton Museum of Art logo. The exact original is preserved in `assets/branding/Norton_Logo_Full_Optimized_Black_RGB.png`, and the web-sized production version is `assets/production/sponsors/norton-museum-of-art-full-black.png`. Do not use the superseded cropped logo.

## Design rule
Implement the approved layout direction faithfully. Do not generate a new concept or redesign unless explicitly requested.

## Exact implementation authority — August 24, 2026
The following published page is the exact layout and styling authority for the corrected build:

https://carajoy.github.io/equalitea-3/EQUALITEA_COMPLETE_DESIGNER_HANDOFF_2026-08-22/EQUALITEA_PRODUCTION_HANDOFF_v1/home.html

- Preserve its home.html structure, section order, card order, class names, grid behavior, spacing, typography, colors, footer treatment, and responsive rules.
- Preserve its styles.css without design or styling edits.
- Apply only the approved owner-supplied copy corrections and approved asset replacements recorded in this handoff.
- Do not reinterpret the reference image or prior mockups in a way that changes the published page.

## Locked burst-capacity production requirement
Approximately 200 event guests may open or refresh the EqualiTEA digital program within the same short time window after scanning the event QR code. The finished implementation and hosting configuration must support this burst of near-simultaneous traffic.

- Keep the page static-first and lightweight.
- Optimize and compress all images for web delivery.
- Use responsive image sizing and lazy-load below-the-fold images.
- Minimize JavaScript. Avoid unnecessary third-party scripts, embeds, trackers, animations, and runtime API calls.
- Core program content, speakers, biographies, sponsors, and navigation must remain available without third-party services.
- Use browser caching and hosting or CDN caching where available.
- Do not load oversized original source images when smaller production versions are sufficient.
- Test mobile performance and simulate burst access appropriate for approximately 200 near-simultaneous guests.
- Flag any hosting, caching, CMS, or server-side limitation before publication.

This requirement is locked. It must remain in final QA and must not trigger a redesign or restart of the approved build.
