# 09 — Codex Kickoff Prompt

Read every numbered `.md` file in this folder before coding, starting with `00_READ_ME_FIRST.md`.

Build the production version of the Women’s Chamber of Commerce of Palm Beach County **3rd Annual EqualiTEA digital program** using this handoff as the source of truth.

## Non-negotiable
Do **not** redesign the page. `assets/reference-layout/EQUALITEA_PROGRAM_LAYOUT.png` is the approved visual and information-architecture reference. Implement it responsively and faithfully.

For this corrected package, the exact layout and styling authority is:

https://carajoy.github.io/equalitea-3/EQUALITEA_COMPLETE_DESIGNER_HANDOFF_2026-08-22/EQUALITEA_PRODUCTION_HANDOFF_v1/home.html

Preserve its home.html structure and styles.css. Make copy and approved asset substitutions only. Do not reorder cards, change classes, alter the grid, restyle the footer, or modify responsive rules.

Do not invent:
- sections
- event copy
- speakers
- biographies
- job titles
- sponsor levels
- sponsor names
- sponsor URLs
- speaker links
- logos

Where sources conflict, follow the precedence in `00_READ_ME_FIRST.md`.

## Build target
Create a fast, mobile-first, framework-neutral webpage package that can be integrated into the existing event page:
https://womenschamber.biz/3rd-annual-tea/

Use semantic HTML and CSS. Use JavaScript only when it improves necessary interaction. Do not use a PDF embed.

## Required section order
Hero → Today’s Program → Today’s Voices → Featured Biographies → Modern Historical Elegance → Sponsors → Committee & Credits → Save the Date 2027

## Interaction
- Same-page anchors for Program, Speakers, Sponsors and About EqualiTEA.
- View Featured Biographies jumps to the biography section.
- Sponsor logos may link only to verified official websites.
- Keep unverified links non-clickable until confirmed.

## Speaker assets
Use physically included headshots where provided.
Source other verified headshots only from the official sources in `08_ASSET_MANIFEST.md`.
Use the user-supplied final approved headshots for Gabrielle Benson, PA-C, MSPAS and Adrienne Percival in `assets/production/headshots/`. Do not use the superseded placeholder files.

## Credit
Use the exact supplied The She’s Online Group logo in Committee & Credits as **Program Design** credit. It is not a sponsor.

## QA before handoff
Produce a local/staging preview and check desktop plus mobile. Compare against the approved layout, validate every name/role/title/organization, test same-page navigation, verify external links, optimize images, and run the full checklist in `07_QA_CHECKLIST.md`.

Treat the approximately 200-guest near-simultaneous arrival requirement in `01_LOCKED_DECISIONS.md` and `06_BUILD_REQUIREMENTS.md` as locked. Preserve the static-first implementation, validate mobile performance, run an appropriate burst simulation, verify or flag the publishing host’s cache behavior, and record results in `PRODUCTION_RUN_SUMMARY.md`.

Do not deploy or overwrite the live Chamber page without explicit approval.
