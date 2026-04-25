# Maple Grove Elementary Community Fund Demo

A GitHub Pages-ready static prototype for a school fundraising, volunteer, event, budget, and sponsor platform.

## Files

- `index.html` contains the full demo site, styles, demo data, and interactions.
- No build step is required.
- The demo uses remote stock image URLs, so it will load images from the web when deployed.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and `README.md` to the root of the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/root`.
6. Save.

## Updating demo content

Open `index.html` and look for the JavaScript arrays near the bottom:

- `events`
- `sponsors`
- `volunteers`
- `budget`

Change those values to replace the demo school data with real data.
