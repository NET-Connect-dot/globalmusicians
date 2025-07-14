# GlobalMusicians Website

## Overview
GlobalMusicians is a platform for musicians to register, appear on an interactive map, and connect globally. It includes registration, profiles, and collaboration features.

## Files
- `index.html`: Homepage with interactive map.
- `register.html`: Registration form for musicians.
- `profile.html`: Profile page for each musician.
- `README.md`: This documentation.

## Hosting Instructions
1. **GitHub Pages**:
   - Create a GitHub repository named `globalmusicians`.
   - Upload `index.html`, `register.html`, `profile.html`, and `README.md`.
   - Go to Settings → Pages, select `main` branch and `/ (root)` folder.
   - Access the site at `https://net-connect-dot.github.io/globalmusicians`.
2. **Local Testing**:
   - Save files to a folder and open `index.html` in Chrome.
3. **Custom Domain (Optional)**:
   - Purchase a domain (e.g., `globalmusicians.app` via Namecheap).
   - In Settings → Pages, add the domain under "Custom domain".
   - Configure DNS in Namecheap (CNAME record to `net-connect-dot.github.io`).

## Managing Data
- Data is stored in `localStorage` (browser-based for MVP).
- To add a backend, use Supabase (free tier):
  - Sign up at https://supabase.com.
  - Create a project and get API keys.
  - Update scripts to send data to Supabase (see documentation).

## Editing the Site
- Modify HTML/CSS in `index.html`, `register.html`, or `profile.html` for design changes.
- Add features (e.g., search or chat) by extending JavaScript.

## Dependencies
- Leaflet.js (v1.9.4): Loaded via CDN for the map.
- No other external dependencies for the MVP.

## Future Expansion
- Add search functionality to filter musicians by instrument/genre.
- Integrate Supabase for permanent data storage.
- Create a collaboration hub for jam session postings.