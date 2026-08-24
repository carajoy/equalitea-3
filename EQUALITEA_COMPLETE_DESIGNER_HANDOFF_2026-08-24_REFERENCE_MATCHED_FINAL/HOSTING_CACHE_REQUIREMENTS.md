# Hosting and Cache Requirements

## Locked event-load requirement

Approximately 200 guests may open or refresh the EqualiTEA digital program within the same short time window after scanning the event QR code. The publishing environment must deliver the static page and its local assets reliably during that burst.

## Current build characteristics

* Static HTML and CSS.
* No JavaScript.
* No runtime API calls.
* No third-party scripts, embeds, trackers, or external font requests.
* Core program content, speakers, biographies, sponsors, and navigation are local and remain available if third-party websites are unavailable.
* Images use optimized production files, responsive sizing, responsive headshot candidates, and below-the-fold lazy loading.

## Required publishing behavior

1. Serve the page through HTTPS from a static-capable host or a CDN-backed website layer.
2. Enable Brotli or gzip compression for HTML and CSS.
3. Apply browser and edge caching equivalent to the included `_headers` file.
4. Keep HTML immediately revalidatable so event updates publish quickly.
5. Cache CSS for at least one hour with stale-while-revalidate support where available.
6. Cache production assets for at least seven days with stale-while-revalidate support where available.
7. Confirm the host does not dynamically render this static program on every request without page caching.
8. Confirm rate limits, bot protection, security rules, or origin connection limits will not reject a short burst of approximately 200 guests.

## Platform limitation to resolve

The included `_headers` file is automatically recognized by some static hosts but may be ignored by WordPress, Apache, IIS, or a managed CMS. If ignored, the web designer or hosting provider must configure equivalent headers through the platform, CDN, caching plugin, server configuration, or host control panel.

The local preview server provides `Last-Modified` metadata but does not currently return `Cache-Control` or CDN cache-status headers. Local testing can validate static concurrency and page behavior, but it cannot certify the final host’s edge cache, geographic delivery, origin capacity, or CMS configuration.

## Final host verification

Before publication approval:

1. Inspect response headers for `/`, `/index.html`, `/styles.css`, and at least one file under `/assets/`.
2. Confirm the intended `Cache-Control` policy is present.
3. Confirm a CDN cache indicator such as `Age`, `X-Cache`, or `CF-Cache-Status` when the selected provider supplies one.
4. Run the approximately 200-user burst test against an authorized staging environment.
5. Record results and any provider limitation in `PRODUCTION_RUN_SUMMARY.md`.

Do not run an aggressive load test against a public production host without the host owner’s authorization.
