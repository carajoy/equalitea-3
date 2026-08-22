# 06 — Build Requirements

## Deliverable
Build a production-ready, mobile-first responsive webpage implementation intended to replace the event-day content on the existing 3rd Annual EqualiTEA page.

Current live destination:
https://womenschamber.biz/3rd-annual-tea/

## Implementation strategy
Because the final site integration method is controlled by the Chamber’s website provider, produce a framework-neutral package first:

- `index.html`
- `styles.css`
- `script.js` only if needed
- `/assets/` with optimized production images
- no unnecessary JavaScript
- no external framework dependency unless a concrete implementation requirement demands it

The code should be portable into a CMS/custom HTML environment.

## Performance
- Design for approximately 200 event guests opening or refreshing the page within the same short time window after scanning the event QR code.
- Keep the page static-first and lightweight.
- Optimize and compress all raster assets for web delivery.
- Use responsive image sizing and smaller production variants where appropriate.
- Lazy-load below-the-fold images.
- Avoid shipping giant original images when smaller web variants will do.
- Do not use a PDF embed as the program.
- Minimize JavaScript. Avoid unnecessary third-party scripts, embeds, trackers, animations, and runtime API calls.
- Core program content, speakers, biographies, sponsors, and navigation must not depend on third-party services being available.
- Use browser caching and hosting or CDN caching where available.
- Test mobile performance.
- Test or simulate burst access appropriate for approximately 200 users arriving within a short period.
- Document any hosting, caching, CMS, or server-side limitation that could affect burst delivery.

The framework-neutral package includes `_headers` as a portable cache-policy starting point. The publishing provider must translate the same policy into its own hosting or CMS configuration if `_headers` is not supported. See `HOSTING_CACHE_REQUIREMENTS.md`.

## Accessibility
- Semantic headings.
- Descriptive alt text for every meaningful image.
- Decorative imagery gets empty alt text.
- Keyboard-accessible navigation.
- Visible focus states.
- Sufficient color contrast.
- Links must be distinguishable.
- Avoid text baked into raster images when it should be live HTML.

## Anchor IDs
Recommended:
- `#program`
- `#speakers`
- `#biographies`
- `#about-equalitea`
- `#sponsors`
- `#credits`
- `#save-the-date`

## Speaker cards
Today’s Voices:
- photo
- name
- professional title
- organization

Do not place full biography copy in the quick-view cards.

## Approved headshot behavior
Gabrielle Benson and Adrienne Percival use the user-supplied final approved headshots in `assets/production/headshots/`.
Do not replace either approved portrait with a temporary placeholder.

## Sponsor links
Open external sponsor destinations normally. Do not invent URLs. Keep unresolved links non-clickable until verified.

## QR
The supplied EqualiTEA QR asset is a project reference. Test its destination before deployment. Do not assume a QR destination is correct merely because the file exists.

## Publication
Do not publish automatically.
First produce a local/staging preview, test it, and obtain approval.
