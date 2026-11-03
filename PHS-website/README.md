# NAU 2026 PHS Sustainability Capstone website

Plain HTML/CSS site. There's no build step and no editor to install: what's in this folder is exactly what gets served.

| File | Page |
|---|---|
| `index.html` | Home |
| `Gallery.html` | Gallery |
| `Documents.html` | Documents |
| `Team-About-Us.html` | Team/About Us |
| `Support.html` | Support |
| `style.css` | Colors, fonts and layout for every page |
| `images/` | Photos |
| `files/` | PDFs |

## Common edits

- **Add a PDF:** put it in `files/`. In `Documents.html`, copy an existing `<li>` line and change the file name and the link text.
- **Add a photo:** put it in `images/`. In `Gallery.html`, copy an existing `<a ...><img ...></a>` line, change both file names, and write a short `alt` description.
- **Change text:** edit the page's `.html` file directly. GitHub's web editor (the pencil icon) works.

File names are case-sensitive on the web: `Photo.JPG` and `Photo.jpg` are different files.

The navigation bar is copied into each of the 5 pages. If you rename or add a page, update the nav in all of them.

## Publishing

- **GitHub Pages:** pushing to `main` updates the site automatically within about a minute.
- **ceias.nau.edu (official course site):** upload the whole folder's contents to the team folder, the same way you uploaded the Nicepage files. Leave out `README.md` and `.nojekyll`.
