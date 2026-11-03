# Lab 5S Audit PWA

This folder contains the installable Progressive Web App version of the Lab 5S Audit demo.

## What changed
- Added a web app manifest and app icons.
- Added a service worker to cache the app shell for offline use after the first successful online visit.
- Added an Install app button when the browser supports the install prompt.
- Added automatic saving of audit entries in this browser on this device using localStorage.
- Kept the original audit screens, team choices, rating flow, comments, photos, review and HTML export.

## Publish it free with GitHub Pages
1. Create or sign in to a GitHub account.
2. Create a new public repository, for example `lab-5s-audit`.
3. Upload **all the contents of this folder** (not just index.html) to the repository root.
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then Save.
7. Wait for GitHub Pages to publish. It will show an HTTPS website address.
8. Open that HTTPS address in Chrome on your Android phone.
9. Use the **Install app** button in the page, or Chrome's ⋮ menu → **Install app** / **Add to Home screen**.

## Important
- The app must be served from HTTPS (GitHub Pages provides HTTPS). Opening index.html directly from Downloads will not enable PWA installation or service-worker offline caching.
- Open the hosted app online at least once before testing offline mode.
- Audit data is saved in the browser storage on that device. It does not automatically sync between phones or computers. Use the app's Export/Download option to make a portable copy.
- Browser storage can be cleared by clearing site data. Export important audits regularly.
- The app is a demo; do not use it as the only record for critical operational or compliance decisions without appropriate testing and approval.
