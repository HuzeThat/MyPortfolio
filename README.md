# MyPortfolio

# Huzeifa .S Portfolio (HTML + CSS)

A simple and responsive personal portfolio website built using **HTML** and **CSS**.  
It includes sections for **About**, **Skills**, **Projects**, **My Certificates**, and **Contact**.

## Features
- Clean single-page layout with smooth navigation
- Responsive cards for Projects
- Expandable certificate groups for:
  - **e-SHE CE102 Certificate**
  - **Udacity (5M coders)**
- Professional UI styling (gradients, shadows, hover effects)

## Project Structure
```text
.
├─ portfolio.html
├─ styles.css
├─ README.md
├─ images/
│  ├─ huze.png.jpg
│  ├─ whether.png.jpg
│  ├─ billing.png.jpg
│  ├─ SocialMedia.png.jpg
│  ├─ farm.png.jpg
│  ├─ Certificate/
│  │  ├─ *.pdf
│  └─ udacity/
│     ├─ *.pdf
└─ TODO.md
```

## How to Run
1. Open `portfolio.html` in your browser:
   - Double-click `portfolio.html`
   - Or use a local server (optional)
2. Certificates open as PDFs in a new tab.

## Customization
### Update Projects
Edit the `#projects` section in `portfolio.html` and replace:
- `img src="images/..."` (project images)
- GitHub links inside the `View on GitHub` buttons

### Update Certificates
Edit the `#certificate` section in `portfolio.html`:
- Change the PDF links to match files inside:
  - `images/Certificate/`
  - `images/udacity/`

## Notes
- PDF filenames with spaces should be URL-encoded (spaces become `%20`) to avoid broken links.
- If you add more certificates, follow the same `<details>` structure used for e‑SHE and Udacity.

## Author
**Huzeifa .S**
