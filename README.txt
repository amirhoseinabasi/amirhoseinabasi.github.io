AMIRHOSEIN ABBASI — PORTFOLIO (GITHUB PAGES)

Package contents:
- index.html: complete bilingual portfolio (English/Persian), RTL/LTR, dark/bright themes, profile image, animations, and two QR actions.
- resume-en.pdf: English résumé opened by the résumé QR action.

Publish with GitHub Pages:
1. Create a PUBLIC repository named USERNAME.github.io.
2. Upload index.html and resume-en.pdf to the repository root (not inside a subfolder).
3. Open Settings > Pages.
4. Under Build and deployment, choose "Deploy from a branch".
5. Select branch "main" and folder "/ (root)", then Save.
6. Open https://USERNAME.github.io after deployment finishes.

QR actions:
1. English résumé: opens resume-en.pdf. The QR destination is constructed from the deployed site URL.
2. Email contact: opens a draft addressed to amirhosseinabbasi1576@gmail.com. Subject and prefilled message switch with the current site language. The visitor must review and send the email themselves.

Both QR cards are also clickable. Keep resume-en.pdf beside index.html in the repository root.

Notes:
- The email QR image is embedded in index.html.
- The résumé QR is generated at runtime using a QR library loaded from a CDN, so an internet connection is required for the QR image to render.
- The website itself is a static single-file HTML page. No build step is required.
