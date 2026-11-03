# Camera Permission Demo

A small, transparent browser demo for learning how camera permissions work.

## Features
- Requests camera access only after the visitor presses **Allow camera & start preview**.
- Uses the browser's normal permission prompt.
- Shows a live preview only; it does not record, upload, or save images or video.
- Provides a **Stop camera** button and stops camera tracks when the page is closed.

## Run locally
Open `index.html` from a local development server. Camera access generally requires HTTPS, or localhost during local development.

## Publish with GitHub Pages
1. Open the repository's **Settings**.
2. Go to **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the default branch and the `/ (root)` folder, then save.
5. Open the published HTTPS URL after GitHub Pages finishes deploying.

Use this demo only on devices where the user has knowingly chosen to grant camera permission.
