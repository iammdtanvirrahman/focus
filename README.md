# Focus — Premium Dark Website Redesign

A responsive homepage redesign for Focus University Admission Coaching, using the visual direction from the supplied current-site screenshots: midnight navy backgrounds, blue/cyan interaction accents, and focused red calls to action.

## Current implementation

- Focus identity cues represented with an inline SVG emblem and Bengali wordmark treatment.
- Premium dark mode by default, with a user-controlled light theme toggle.
- Responsive sticky navigation, mobile menu, desktop/mobile course search, and category filters.
- Separate public-homepage and online-portal entry flow: `/` is the public marketing site; `/online/` forwards students to Focus's existing secure login; the existing Focus backend continues to handle authentication and the post-login student portal.
- Course cards with Focus course thumbnails and live public links for Science, Humanities, Business Studies, exam batches, second-time batches, and the free course.
- Student achievement cards based on stories visible on the current Focus homepage.
- Student services section for online/offline programs, Q&A, free course, materials, absent/result support, and branch discovery.
- University-destination tiles, contact CTA, floating WhatsApp shortcut, and back-to-top control.
- Reduced-motion support and mobile-specific layouts.

## Preview

Open `index.html` directly, or use a local static server. No build step is required.

## Publish on GitHub Pages

A workflow at `.github/workflows/deploy.yml` attempts to publish the static website automatically whenever `main` is updated and can also be run manually from **Actions**.

1. Open **Settings → Pages** and make sure the deployment source is **GitHub Actions**.
2. Open **Actions → Deploy Focus website to GitHub Pages**.
3. Check the latest run. When it succeeds, open the published Pages URL from the workflow run or repository Settings → Pages.

## Important implementation notes

- This is a front-end prototype; it links to Focus's existing public course pages, student login, teacher login, branches, contact, and success stories.
- Login, enrollment/payment, student results, Q&A, SMS, and administration remain powered by Focus's existing systems. The `online/` entry page forwards to the existing login and does not collect credentials or simulate authentication. This static site does not implement or replace those backends.
- Course prices, class counts, and success-story details should be rechecked by Focus before production launch because program information can change by session.
- The inline vector is a brand-inspired recreation based on the provided screenshot, not the original high-resolution source logo. Replace it with the official transparent logo asset if Focus provides one.
