AUTO LEVEL SURVEY — COMPLETE WEB APP PACKAGE

FILES
- index.html: main application (survey dashboard, level book, saved road surveys, portable HTML save)
- manifest.webmanifest: PWA installation metadata
- sw.js: service worker and offline cache
- icons/: 192px and 512px home-screen icons
- images/: original SVG logo
- favicon-16.png, favicon-32.png, apple-touch-icon.png: browser/mobile icons

UPLOAD TO GITHUB PAGES
1. Download and extract this ZIP.
2. Open your GitHub repository: Level_Book.
3. Upload ALL files and folders from inside the extracted package to the repository ROOT (not the ZIP itself and not an extra enclosing folder).
4. Replace existing files when asked, then commit changes to branch main.
5. In Settings > Pages, choose Deploy from a branch, branch main, folder /(root).
6. Wait for deployment to finish, then open https://aarnjhn.github.io/Level_Book/ in Chrome.
7. Refresh the page. If Chrome still has old cached app files, open site settings for the site, clear its storage, then revisit and try Install again.

IMPORTANT
- Keep the exact filenames and folder names.
- The icons must stay inside the icons folder.
- The manifest uses relative paths so the package works under a GitHub Pages project path such as /Level_Book/.
- After uploading, confirm that index.html, manifest.webmanifest, sw.js, icons/, and images/ are all visible at the top level of the repository.
