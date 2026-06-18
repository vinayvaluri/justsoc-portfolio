# JustSOC — Professional Cybersecurity Portfolio & Services

This repository contains a single-file static landing page for JustSOC — a professional cybersecurity portfolio and fractional Cloud Security Architect services landing page.

Contents
- index.html — the full static site (single page).

What I changed
- Added this README.md with a short project description and deployment notes.
- Added a LICENSE (MIT) file.
- Added basic SEO/meta tags, Open Graph and Twitter card tags to index.html.
- Added preconnect hints for Google Fonts and a favicon link.
- Added a prefers-reduced-motion CSS rule to respect users' motion preferences.
- Added an id="top" anchor to the <body> and replaced the smooth-scroll script with a safer version that checks the target exists before calling scrollIntoView.

Deployment
- This is a static site. You can deploy to GitHub Pages, Cloudflare Pages, or any static host. On GitHub Pages: enable Pages for the main branch (root) in repository settings.

Notes & next steps
- Consider adding a favicon (favicon.ico) and an Open Graph image (/og-image.png) used by the meta tags.
- Consider switching to a Tailwind build process (npm + tailwindcss) to purge unused CSS and to avoid runtime CDN tailwind usage.

Contact
- contact@justsoc.in
