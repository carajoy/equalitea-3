# 3rd Annual EqualiTEA Digital Program

Production-ready digital program for the Women’s Chamber of Commerce of Palm Beach County 3rd Annual EqualiTEA on August 26, 2026, at The Ben in West Palm Beach.

## Start here

The program is already designed and built. Do not recreate it from the source documents.

Open `index.html` to review the finished page. This is a static HTML and CSS project with no build command, JavaScript framework, runtime API, third-party script, embed, tracker, or external font dependency.

## Publication files

Keep these items together with their existing names and folder structure:

* `index.html`
* `styles.css`
* `assets/`
* `_headers`, or an equivalent cache configuration on the selected host

`index.html` is the entry page. Read `HOSTING_CACHE_REQUIREMENTS.md` before publication.

## Locked traffic requirement

Approximately 200 event guests may open or refresh the digital program within the same short time window after scanning the event QR code.

The build must remain static-first, lightweight, cacheable, independent of third-party services for core content, and optimized for mobile delivery. The actual publishing host or authorized staging environment must pass the cache and burst checks documented in `HOSTING_CACHE_REQUIREMENTS.md` and `07_QA_CHECKLIST.md`.

## Completed owner revisions

* Angela Manfredi’s credentials appear in program item 2.
* The page contains exactly four Featured Biographies.
* Gabrielle Benson’s and Adrienne Percival’s supplied portraits are the final approved headshots, not placeholders.
* The approved spelling is `Adrienne Percival`.
* Gabrielle Benson is displayed as `Gabrielle Benson, PA-C, MSPAS` with Palm Beach Health Network and Memorial Sloan Kettering Cancer Center.
* The complete official Florida Weekly logo is installed.
* Program Design uses only The She’s Online Group logo.
* LinkedIn points to `https://www.linkedin.com/company/wccpbc`.
* Facebook and Instagram use `@wccpbc`.

Historical source files may contain superseded wording or the outdated `Perceval` spelling. The current production page and controlling Markdown files are authoritative.

## Performance and QA status

* 0 JavaScript files.
* 0 runtime API calls.
* 0 third-party content dependencies.
* 186.6 KB critical first-load package before transfer compression.
* 50 optimized production assets totaling 2.20 MB.
* 48 of 49 rendered images use lazy loading.
* 17 headshot placements use responsive `srcset` and `sizes` rules.
* 0 missing local references.
* 0 broken browser images.
* 0 browser console warnings or errors.
* Desktop and phone responsive checks passed.
* 200 of 200 simultaneous page requests passed on a cache-configured static test server.
* 800 of 800 critical-file requests passed in the 200-guest simulation.

The basic local preview server did not pass raw 200-request concurrency and must not be used as the event host. The actual CMS, host, and CDN remain subject to final authorized staging verification.

## Source of truth

Read these files in order before changing production content:

1. `00_READ_ME_FIRST.md`
2. `01_LOCKED_DECISIONS.md`
3. `02_SPEAKER_ROSTER.md`
4. `03_BIOGRAPHIES.md`
5. `04_SPONSORS_AND_LINKS.md`
6. `05_DESIGN_AND_LAYOUT_SPEC.md`
7. `06_BUILD_REQUIREMENTS.md`
8. `07_QA_CHECKLIST.md`
9. `08_ASSET_MANIFEST.md`
10. `09_CODEX_KICKOFF_PROMPT.md`
11. `HOSTING_CACHE_REQUIREMENTS.md`
12. `PRODUCTION_RUN_SUMMARY.md`

Original files under `source-documents/` and reference assets remain included for provenance and future revisions.

## Deployment status

Nothing has been deployed from this package.
