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

## Design rule
Implement the approved layout direction faithfully. Do not generate a new concept or redesign unless explicitly requested.

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
