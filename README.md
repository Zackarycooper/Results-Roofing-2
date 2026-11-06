# HomeMap — Free Edition

A small, installable property-notes map. Records are stored in the current browser using local storage; they are not synced to an account or another device. Use **Export backup** regularly.

## Run locally

Serve this directory over HTTP (for example, with a local static web server) or publish it with GitHub Pages. Opening `index.html` directly as a `file://` preview may prevent external scripts and map tiles from loading.

## Publish with GitHub Pages

1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the default branch and `/(root)`, then save.
4. Open the published HTTPS URL in a browser. On iPhone Safari, use **Share → Add to Home Screen**.

## Features

- OpenStreetMap street tiles and Esri World Imagery satellite layer.
- Address search through the public OpenStreetMap Nominatim geocoder.
- Add, edit, select, and delete property notes on a map.
- Export/import JSON backups and store records locally in the browser.
- Map loading diagnostics and a retry button.

## Privacy and providers

Property records stay in this browser on this device unless you export or import them. Browser storage is not encrypted, synced, or a cloud database. Do not store alarm codes or other sensitive information. Map tiles and address search require internet access and are subject to their providers' availability, terms, and usage policies. Avoid excessive searches; Nominatim is a community service with a usage policy.

GitHub Pages is third-party hosting and is not an account or cloud database for property records.
