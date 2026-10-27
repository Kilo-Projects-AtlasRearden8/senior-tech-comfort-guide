# STATUS.md

## What was built

A beginner-friendly, large-print manual on everyday technology for seniors, published as a static HTML site. The project lives in `/workspace/kilo-lab/senior-tech-comfort-guide`.

Files:

- `README.md` — project overview, contents, how to use, accessibility notes, license, credits to Asdale Dynamics, LLC
- `LICENSE` — MIT License, copyright line exactly `Copyright (c) 2026 Asdale Dynamics, LLC`
- `assets/css/style.css` — large-print stylesheet (18px body text, high contrast, roomy spacing, print-friendly)
- `docs/index.html` — welcome page and guide overview
- `docs/phones.html` — making/answering calls, saving contacts, voicemail
- `docs/email.html` — sending/replying, attachments, inbox cleanup
- `docs/video-calls.html` — Zoom, FaceTime, Google Meet step by step
- `docs/passwords.html` — strong passwords, password managers, two-step verification
- `docs/text-size.html` — bigger text on iPhone, Android, Windows, Mac, and browsers
- `docs/scam-avoidance.html` — spotting and handling phone, email, text, and website scams

Every page uses plain English, numbered step-by-step checklists, tip boxes, caution boxes, and consistent navigation. Each page credits Asdale Dynamics, LLC in the footer.

## How to run

No installation, no build step, and no internet connection are required.

1. Open the `docs/` folder.
2. Double-click any `.html` file (or right-click → Open With → your web browser).
3. Pages can also be printed; a print stylesheet hides navigation and buttons for clean large-print output.

## Verification results

- All 7 HTML pages parse without syntax errors.
- All internal links between pages resolve correctly (no broken links).
- CSS classes used in HTML match classes defined in `assets/css/style.css` (including the `.tip-text` inline-tip class).
- Git initialized and committed as `Dylan Asdale <dylanasdale@users.noreply.github.com>` with a plain commit message and no co-author trailers.
- No `.github/workflows` files added. No secrets, API keys, or personal data in any file.

## Known gaps

- This is a static HTML site with no build pipeline, tests framework, or linting step beyond the manual link/class checks above.
- No images or icons were added; the design relies on typography and color only.
- External links (e.g. `dylanasdale.github.io`, `reportfraud.ftc.gov`) require an internet connection and were not fetched for validation.
