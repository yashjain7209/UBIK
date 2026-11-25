# UBIK Solutions Homepage

A single-page homepage for UBIK Solutions.

## Files
- `index.html`: the homepage, with the hero text left-aligned. CSS and JavaScript are inline.
- `index-center.html`: the same page with the hero text centered, kept for comparison.
- `assets/`: images, logos and videos the pages load.

## Running it
Open `index.html` in a browser, or serve the folder with any static server, for example:

```bash
python3 -m http.server 8000
```

The page loads the Manrope font from Google Fonts and GSAP, ScrollTrigger and Lenis from public CDNs, so it needs an internet connection for fonts and scroll animations.

## Publishing on GitHub Pages
In the repository, open Settings, then Pages, choose "Deploy from a branch", select `main` and `/ (root)`, and save. The site is then served at `https://<user>.github.io/<repo>/`.
