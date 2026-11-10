KONASEEMA PARAMPARA - WEBSITE PROJECT
=====================================

FOLDER CONTENTS
- index.html: website homepage
- assets/: all local product and category images used by the website
- website-preview.png: reference preview image

RUN ON YOUR LAPTOP
1. Extract the ZIP completely.
2. Open the konaseema_parampara_site folder.
3. Keep index.html and the assets folder together. Do not move or rename assets.
4. Double-click index.html to open it in Chrome, Edge, or Firefox.

GITHUB (WINDOWS)
1. Install Git for Windows: https://git-scm.com/download/win
2. Create an empty GitHub repository named konaseema-parampara.
3. Open this folder in File Explorer. Click the address bar, type powershell, and press Enter.
4. Run these commands one at a time (replace YOUR-USERNAME):

   git init
   git add .
   git commit -m "Add Konaseema Parampara website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/konaseema-parampara.git
   git push -u origin main

IMPORTANT: git add . uploads the assets folder and its images too.

NETLIFY DEPLOYMENT
Import the GitHub repository in Netlify. This is a static HTML site: leave the build command blank. Set the publish directory to the repository root (.) if the repository contains index.html and assets/ at its top level.

IMAGE TROUBLESHOOTING
- Correct structure: index.html beside assets/ (not inside it).
- Upload the entire folder contents to GitHub, not only index.html.
- File names are case-sensitive after publishing. Do not rename image files.

ORDERING NOTE
This is a frontend prototype. WhatsApp checkout requires your real business WhatsApp number to be configured. A central order dashboard/database is a separate backend feature and is not included in this static project.
