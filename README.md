# iCAT Lab Website

Official website of the Intelligent Computer Architecture & Technology (iCAT) Lab at the University of Central Florida.

## GitHub Pages deployment

This repository is prepared for deployment at:

<https://ucf-icat.github.io/>

For that exact address, create the repository under the `ucf-icat` GitHub account or organization with this exact name:

```text
ucf-icat.github.io
```

Upload the contents of this directory to the repository root. In GitHub, open **Settings → Pages**, select **Deploy from a branch**, then choose the `main` branch and `/ (root)` folder.

No build step or external package installation is required. The website consists of static HTML, CSS, SVG, and image assets.

## Pages

- `index.html` — Home
- `research.html` — Research
- `people.html` — People
- `publications.html` — Publications and patents
- `news.html` — News
- `join.html` — Join the lab

## Local preview

From the repository directory, run:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000/>.

