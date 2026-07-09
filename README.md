# m-salmani78.github.io

Personal academic website hosted on GitHub Pages at [https://m-salmani78.github.io](https://m-salmani78.github.io).

Inspired by [vavre.github.io](https://vavre.github.io/).

## Structure

```
├── index.html          # Main page
├── My_CV.md            # CV source (markdown)
├── css/style.css       # Styles
├── js/main.js          # Mobile nav & scroll-spy
├── images/profile.svg  # Profile placeholder (replace with your photo)
└── favicon.svg
```

## Customization

1. **Profile photo** — Replace `images/profile.svg` with your photo (e.g. `images/profile.jpg`) and update the `src` in `index.html`.
2. **About & News** — Edit the About Me and News sections in `index.html` directly.
3. **CV content** — Update `My_CV.md`, then sync changes into `index.html`.
4. **Download CV** — Add a PDF to the repo and point the "Download CV" button to it (e.g. `CV_Salmani.pdf`).

## Local preview

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

GitHub Pages deploys from the `main` branch root. Push to `main` and the site updates within a minute or two.
