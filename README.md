# Shaurya Mani — Student Portfolio

Simple static portfolio site built with HTML and CSS.

## Summary
This repo contains a small personal portfolio with:
- A responsive navbar (logo + links)
- Home hero ("It's me, hi, I'm Shaurya.") centered on the page
- About page
- Skills page with skill bars
- Contact page with a basic HTML form (no JavaScript)

## Get started (Windows)
1. Clone or download the repo to your PC.
2. Open the project folder in your browser or a simple HTTP server.

To open directly:
- Double-click `index.html` (works but some browsers may block local fonts/assets).

To serve with Python (recommended):
- In PowerShell or CMD, run:
  - python 3: `python -m http.server 8000`
  - or: `py -m http.server 8000`
- Open http://localhost:8000

## File structure
- index.html — Home / hero
- about.html — About page
- skills.html — Skills page
- contact.html — Contact form
- style.css — All styles
- images/ — logo and background image(s)

## Quick customizations
- Change logo: replace `images/logo.png` and keep same filename, or update `<img src="...">`.
- Change background: replace `images/background.jpg` or update `body { background-image: url(...) }` in `style.css`.
- Edit hero text: modify the H1 in `index.html`.
- Update skills: edit `skills.html` (.skill elements) and adjust `.skill-level` widths inline or via classes.

## Notes
- No JavaScript used — form is basic HTML only.
- Fonts loaded from Google Fonts in the HTML head.
- Keep images in the `images/` folder for links to work as-is.

## License
Use freely for personal/learning purposes.

## Contact
For edits or questions, modify the files directly in this repo.
