# Syed Talha Safeer Portfolio Website

This is a free static portfolio website for GitHub Pages. It uses only:

- `index.html` for content and sections
- `style.css` for design, colors, layout, and mobile responsiveness
- `script.js` for mobile menu, dark mode, active navigation, scroll animations, and the email form
- `assets/` for images, icons, and placeholders

No paid hosting, database, backend, or build step is required.

---

## Folder structure

```text
profile-website/
├── index.html
├── style.css
├── script.js
├── README.md
├── .nojekyll
└── assets/
    ├── favicon.svg
    ├── logo.svg
    ├── og-image.svg
    ├── profile-placeholder.svg
    ├── hero-technology.svg
    ├── project-linac.svg
    ├── project-beamline.svg
    ├── project-embedded.svg
    ├── project-pv.svg
    ├── project-afc.svg
    └── project-automation.svg
```

---

## How to edit your information

Open `index.html` in VS Code and search for `EDIT:` comments.

You can change:

- Name and title
- Introduction
- Education
- Experience
- Skills
- Projects
- Publications
- Email
- LinkedIn
- Mobile number
- GitHub link

---

## How to replace images

All images are in the `assets` folder.

Recommended replacements:

- Replace `assets/profile-placeholder.svg` with your own photo.
- Replace project SVG files with your own project images if required.
- Keep the same file names if you do not want to change the HTML code.

If you use a different file name, update the `src=""` path in `index.html`.

Example:

```html
<img src="assets/my-photo.jpg" alt="Syed Talha Safeer profile photo" class="profile-image" />
```

---

## How to upload to GitHub

Your repository is:

```text
https://github.com/Talha-Safeer/profile-website
```

Steps:

1. Download and extract the ZIP file.
2. Open the extracted folder.
3. Upload the files and the `assets` folder into the root of your GitHub repository.
4. Make sure `index.html` is directly in the repository root, not inside another folder.
5. Go to repository **Settings → Pages**.
6. Select **Deploy from a branch**.
7. Select branch **main** and folder **/root**.
8. Save.

Your website should appear at:

```text
https://talha-safeer.github.io/profile-website/
```

GitHub Pages may take a few minutes to deploy.

---

## Important note about uploading folders

If the GitHub web upload screen does not show a folder upload button, drag the complete `assets` folder from Windows File Explorer into the GitHub upload area. Modern browsers usually keep the folder structure.

Alternative method: install GitHub Desktop, clone the repository, copy all files into the local repository folder, then commit and push.

---

## Contact form note

This is a static website. The contact form uses `mailto:` and opens the visitor's email app.

To change the email address, open `script.js` and replace:

```js
mailto:your.email@example.com
```

with your real email.
