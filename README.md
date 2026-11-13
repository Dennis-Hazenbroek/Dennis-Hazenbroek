# Dennis Hazenbroek — IT Professional Portfolio (Version 3)

A responsive, static portfolio website built with HTML, CSS and JavaScript. It has no server-side dependencies, build process or Python requirement and is suitable for GitHub Pages or conventional static hosting.

## Version 3 improvements

- Retains the existing dark navy and turquoise visual identity.
- Adds prominent CV downloads in PDF and Word formats.
- Refines the professional profile and selected IT employment history using the latest CV supplied.
- Expands project summaries and clearly distinguishes public repository links from work that does not yet have a dedicated public repository.
- Improves mobile navigation, including Escape-key handling and focus visibility.
- Adds social preview metadata, semantic landmarks, skip navigation and reduced-motion support.
- Includes a direct email contact button using the address explicitly approved for publication: donagh.thebard@gmail.com.

## Files

- `index.html` — page content and structure
- `styles.css` — design and responsive layout
- `script.js` — mobile navigation and footer year
- `assets/Dennis_Hazenbroek_CV.pdf` — downloadable PDF CV
- `assets/Dennis_Hazenbroek_CV.docx` — editable Word CV
- `.nojekyll` — disables unnecessary Jekyll processing on GitHub Pages

## Preview locally

Extract the ZIP and open `index.html` in Firefox, Chrome or another modern browser. No local server or Python installation is required.

## Publish to GitHub Pages

1. Open your portfolio repository on GitHub.
2. Upload the **contents** of this folder to the repository root (not the containing folder). `index.html` must be at the top level.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)` folder, then save.
6. Wait for GitHub Pages to finish deploying. The Pages settings screen will show the published address.

If you use a custom domain, configure it in **Settings → Pages → Custom domain** and follow GitHub's DNS instructions at your domain provider.

## Project links

- Library Management System: https://github.com/Dennis-Hazenbroek/Library-system
- Expenses Tracker: https://github.com/Dennis-Hazenbroek/expenses_tracker
- GitHub profile: https://github.com/Dennis-Hazenbroek

## Before publishing

- Review all employment dates and descriptions against your records.
- Check that the CV is the version you want employers to download.
- Check that each public repository is ready for recruiters to inspect.
- The contact section includes a `mailto:` button and visible email address. The published address is `donagh.thebard@gmail.com`; change both mail links in `index.html` if you ever want to use a different address.

## Accessibility and testing

The site includes a skip link, semantic page landmarks, visible keyboard focus, accessible mobile-menu state, responsive layouts and reduced-motion handling. Check the finished page on a phone and desktop after publishing, and test each CV download and GitHub link.
