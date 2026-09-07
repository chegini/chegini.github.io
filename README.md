# Fatemeh Chegini website

Personal academic and research website for Fatemeh Chegini, built with Hugo and the HugoBricks theme.

## Local development

Requirements:

- Hugo Extended

Run the local preview:

```bash
hugo server
```

Then open <http://localhost:1313/>.

Create a production build locally with:

```bash
hugo --minify
```

The generated site is written to `public/`.

## GitHub Pages

The repository includes a GitHub Actions workflow in `.github/workflows/hugo.yml`. It builds the Hugo site and deploys it to GitHub Pages whenever changes are pushed to `main`.

In the repository settings, open **Pages** and set the source to **GitHub Actions**. After the workflow completes, the site is available at:

<https://chegini.github.io/>

## Content

- `content/en/_index.md`: homepage
- `content/en/research.md`: research themes
- `content/en/publications.md`: publications
- `content/en/talks.md`: conference talks
- `content/en/contact.md`: contact information
- `content/en/cv.md`: education and CV link
- `static/uploads/`: photographs, video, figures, reports, slides, and CV files
