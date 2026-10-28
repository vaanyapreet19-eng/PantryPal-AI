# Pantry Pal AI landing page

A responsive, static landing page inspired by the supplied Pantry Pal AI poster. It uses plain HTML, CSS and JavaScript, so it can be hosted on GitHub Pages without a build step.

## Files
- `index.html`: page content and sections
- `style.css`: responsive design and visual styling
- `script.js`: mobile navigation and current year
- `assets/favicon.svg`: site icon
- `assets/original-poster.png`: original poster reference supplied for this build

## Preview locally
Open `index.html` in a modern browser. For a closer local development workflow, run a static server from this directory, for example `python -m http.server 8000`, then visit `http://localhost:8000`.

## Publish free with GitHub Pages
1. Create or sign in to a GitHub account.
2. Create a **public** repository named `pantry-pal-ai`.
3. Upload the contents of this folder to the repository root. Make sure `index.html` is at the top level, not nested in another folder.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then click **Save**.
7. Wait for the Pages deployment to finish. The URL will look like `https://YOUR-USERNAME.github.io/pantry-pal-ai/`.

## Before publishing
- Replace `hello@pantrypal.ai` with a real contact email or signup URL.
- Update the proposed $4.99/month premium price if it is not final.
- Add real Apple App Store / Google Play links only after the apps are published.
- Add your actual privacy policy and terms if you collect personal information.
- Do not add API keys or secrets to this static site. GitHub Pages serves public files.
- This landing page is a promotional website, not a working pantry database or AI backend.

## Design notes
The phone screen is recreated in HTML/CSS, rather than using the poster as a single image. This keeps the page responsive and the text accessible. Google Fonts are loaded externally; the site uses fallback fonts if unavailable.
