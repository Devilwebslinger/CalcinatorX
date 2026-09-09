# Naini Calcinator

A mobile-first calculator web app / Progressive Web App (PWA).

## GitHub installation

1. Create a GitHub repository.
2. Upload **all files in this folder** to the repository root.
3. Enable **GitHub Pages** from the repository's Settings → Pages.
4. Open the generated **HTTPS** Pages URL in Chrome.
5. Chrome should offer **Install app** / **Add to home screen**.

The app includes a web app manifest and service worker, so it can run as an installable PWA when served over HTTPS.

## Important

Opening `index.html` directly as `file://` will not provide normal service-worker/PWA installation. Use GitHub Pages (or another HTTPS web host).
