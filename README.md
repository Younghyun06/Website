# My Journey Website

This repository contains a small static website that will tell the story of my move from Korea to the United States, host my resume, and highlight my research.

Quick start (open locally):

PowerShell commands:

```powershell
# from the repository root
python -m http.server 8000; Start-Process "http://localhost:8000/index.html"
```

Or just open `index.html` in your browser.

How to edit:
- Update the HTML files in the repo.
- Put images and PDFs in `assets/` and reference them from pages.

Deploy:
- Push to GitHub and enable GitHub Pages from the repository settings (use `main`/`master` or `gh-pages`).

