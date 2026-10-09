# The Garden Girl

A complete responsive static website. No package installation, build step, or backend required.

## Upload to GitHub and connect to Vercel
1. Extract this ZIP.
2. Upload the CONTENTS of the garden-girl folder to the root of your GitHub repository: index.html, styles.css, script.js, README.md, and the entire assets folder.
3. Import the repository in Vercel. Choose framework preset **Other**, leave the build command empty, and use the repository root as the output directory (or leave the output setting at its default).
4. Deploy. Changes committed to the connected repository will trigger a new deployment.

## Content and features
- Modern farmhouse cream, sage, and blush design.
- Wedding flower bar as the signature service, plus fresh preorders and custom artificial arrangements.
- Project-based pricing; no invented packages, service area, reviews, or contact details.
- Hallie's supplied story and all six supplied arrangement images.
- Supplied LeadConnector contact iframe and resizing script, plus a direct form fallback link.
- Mobile navigation and accessible gallery lightbox.
- Wayfinder Creative logo and linked footer credit.

## Add Hallie's portrait
Hallie Portrait.jpeg was not included among the files available for this build. The About section currently shows one of Hallie's arrangements, accurately labeled as an arrangement. To add her portrait:
1. Save it as assets/hallie-portrait.jpeg.
2. Find the comment “Add assets/hallie-portrait.jpeg” in index.html.
3. Change the following image src to assets/hallie-portrait.jpeg and its alt text to “Hallie Williams, owner of The Garden Girl”.

## Photos
All img_*.jpg photos are the supplied examples of Hallie's work. The general floral inspiration image is from Unsplash (https://unsplash.com/photos/88aa4486c946; image source https://images.unsplash.com/photo-1490750967868-88aa4486c946). It is labeled as inspiration and does not claim to show Hallie's flower-bar setup or artificial arrangements. There is no real flower-bar or artificial-arrangement photo supplied, so those services are presented with descriptive copy rather than mislabeled examples. Replace inspiration with actual service photography as it becomes available.

## Easy edits
- Text and links: index.html
- Colors, spacing, responsive layout: styles.css
- Menu and gallery behavior: script.js
- Photos: assets/

Google Fonts loads DM Sans and Libre Caslon Display; system fonts are used if unavailable. All photos are bundled locally.

## Before launch
Open on a phone and computer; confirm the external contact form renders and submit a test inquiry yourself to confirm it reaches Hallie's GHL inbox. The third-party form's fields, notifications, consent, and settings are managed in GHL. Service links show a prompt above the form; they do not fill fields inside the external iframe. This package was checked for local file references and JavaScript syntax. Live third-party form delivery was not tested, and no inquiry was submitted.
