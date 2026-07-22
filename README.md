# Ben Stef — Personal Website

![Ben Stef](profile.jpg)

This repository contains the static sources for my personal website, published at: https://bstef.github.io

Purpose
- Serve a simple, fast personal portfolio and contact page.
- Demonstrate systems engineering and web projects.

Quick preview (local)
1. Clone the repo:

	git clone https://github.com/bstef/bstef.github.io.git
	cd bstef.github.io

2. Preview locally (Python 3):

	python3 -m http.server 8000
	# then open http://localhost:8000 in your browser

Development notes
- Pages are plain HTML and CSS (no build step). Edit `index.html` and supporting pages directly.
- Assets like `profile.jpg` live at the repo root.
- Theme toggle and small interactive scripts are in `index.html`.

Deploying
- This repo is served by GitHub Pages from the `main` branch — pushing to `main` publishes changes.

Suggested workflow
- Create a branch for larger changes, test locally, open a PR, then merge to `main`.

Adding a favicon
- The site currently uses `profile.jpg` as the favicon. For best browser support, add `favicon.ico` and `favicon-32x32.png` and update the `<head>` link tags.

Contact
- LinkedIn: https://linkedin.com/in/bstef
- Portfolio: https://bstef.com

License & copyright
- © 2026 Ben Stef. All rights reserved.

If you'd like a more detailed CONTRIBUTING guide, automated preview branch (Netlify/Vercel) setup, or a small build pipeline, I can add that next.
