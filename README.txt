TAOBIN FINDER — DEPLOYMENT NOTES

This folder contains a mobile-friendly web app built from your exported Google My Maps KML file.

To publish with GitHub Pages:
1. Sign in to github.com and create a new PUBLIC repository (for example: taobin-finder).
2. Upload all four files in this folder (index.html, manifest.webmanifest, icon.svg, sw.js) to the repository root.
3. In the repository, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
5. Wait for GitHub Pages to publish. Open the published https://...github.io/... address in Safari on your iPhone.
6. Tap Safari Share > Add to Home Screen.
7. Open the home-screen app and tap Find machines near me. Allow location access.

Notes:
- The app contains the 93 locations from the supplied KML (91 OPERATING, 2 STANDBY).
- GPS permission is requested only when you tap Find machines near me.
- Distances are straight-line estimates, not walking/driving distances.
- Directions open Google Maps.
- The map uses OpenStreetMap tiles and Leaflet from their public CDNs, so an internet connection is needed.
