# a3ss.com — marketing site

Single-page static site for A3S LLC (rideshare car rental, Irving TX).
No build step, no dependencies: `index.html` is the whole site, with the logo
and all styles inlined so the page makes zero external requests.

- `index.html` — the site
- `preview.html` — same page without the document wrapper, for preview hosting
- `assets/logo.jpg` — source logo

## Editing
Everything lives in `index.html`. Rates, requirements and contact details are
plain text in the markup.

## Not yet wired
The application form shows a confirmation but does not submit anywhere. It is
built to post into the A3S Driver Accounting sheet via Apps Script.
