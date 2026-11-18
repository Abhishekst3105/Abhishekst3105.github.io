# Abhishek S T — Unity Developer Portfolio

A responsive, static portfolio introducing Abhishek S T and showcasing Unity 2D applications and an IoT project. The site uses semantic HTML, CSS, and vanilla JavaScript; it has no build step, package dependencies, or backend requirement.

## Technologies

- HTML5 for the homepage and project detail pages
- CSS3 for layout, responsive styling, light/dark themes, and image placeholders
- Vanilla JavaScript for theme persistence and the mobile navigation menu
- System fonts and inline SVG icons; no external font or icon service is required

## Project structure

```text
.
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   ├── images/
│   └── videos/
├── projects/
│   ├── delivery-crash.html
│   ├── smart-agriculture.html
│   └── snow-surfer.html
└── README.md
```

The `assets/images/` and `assets/videos/` folders currently contain no project media. Project thumbnails and galleries are clearly labelled placeholders. No resume file is currently available, so the resume button is disabled until an actual file is added.

## Run locally

No dependencies or build tools are needed. Open `index.html` in a browser to preview the site. Alternatively, run a local static-file server from the repository root:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`. This is only for local preview; the published site is static and does not require a server-side application.

## Deploy with GitHub Pages

1. Push the site files to the `main` branch.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/(root)` folder, then save.
5. Wait for the Pages deployment to complete. For this user-site repository, the expected URL is `https://Abhishekst3105.github.io/`.

The site uses relative paths for its stylesheet, script, and project pages, so it can be served from the repository root without a build or backend.

## Before publishing

- Add the actual resume file under `assets/` and update the disabled resume button in `index.html` to link to that file.
- Add real screenshots under `assets/images/` and replace the labelled placeholders on the homepage and project detail pages.
- Add a public contact email and LinkedIn profile URL only if you want them shown; the current page leaves both as placeholders.
- Review all public portfolio content and links before publishing. Do not commit credentials, private keys, or other secrets.

## Customize

- Edit homepage content and navigation in `index.html`.
- Edit each project case study in `projects/`.
- Adjust layout, colors, and responsive breakpoints in `css/style.css`.
- Adjust theme and menu behavior in `js/script.js`.
