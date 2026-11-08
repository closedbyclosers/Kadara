# kadara™ medical — Disposable Trocar Kit landing page

A single-file landing page (`index.html`) for kadara™ medical with an interactive 3D tour of the 19130SG Disposable Trocar Kit.

## What's inside
- **Interactive 3D kit**: scroll to peel the lid, then click any piece in the tray to lift it out and spin it (Three.js).
- **Every piece, up close**: all 13 kit components plus the Stainless Steel and Titanium Reusable Trocar Sets, each viewable in 3D or as a photo.
- **FlexiKit** 3D viewer, kit configurator / "Find my kit" funnel, reorder links.
- **Video library**, testimonials, The People, FAQ's, network sign-up form.
- Footer policies (Refund, Privacy, Terms, Contact Information) open in on-page pop-ups.

## Run locally
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

An internet connection is needed for Three.js (jsDelivr CDN), Google Fonts, the videos and product links on kadaramedical.com. Product photos and team headshots are embedded in the file.

## Deploy
- **GitHub Pages**: Settings → Pages → Deploy from branch → `main` / root.
- **Netlify**: drag-and-drop the folder or connect the repo. The network form uses Netlify Forms (`data-netlify="true"`), so submissions show up in the Netlify dashboard.
- Any static host works — there is no build step.
