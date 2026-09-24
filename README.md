# Strength App

A vanilla HTML, CSS, and JavaScript starting point for a strength-training PWA.

## Preview locally

Serve the project directory over HTTP (service workers do not work from a `file://` URL). For example, with Python:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Publish with GitHub Pages

In the repository's **Settings → Pages**, choose the `main` branch and the `/ (root)` folder as the publishing source. The app is built from relative URLs so it also works when published under a path. Once the site is published, configure `www.strength.berdalsanner.no` as the custom domain in Pages and point its DNS records to GitHub Pages.

The service worker caches the app shell after the first visit. Browser install prompts and offline support require HTTPS; GitHub Pages provides HTTPS for the published site.
