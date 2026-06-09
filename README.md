# Personal Portfolio — N. Omkar Vardhan

My personal portfolio website. Built it from scratch using plain HTML, CSS, and vanilla JS — no frameworks, no build tools, just open the file and it works.

Live at: portfolio-ov.vercel.app

---

## What's in it

- **Hero section** with a particle canvas background, typing animation, and profile photo
- **About** — a short writeup about who I am and what I'm working towards
- **Skills** — split into things I know and things I'm currently learning, with animated progress bars
- **Education timeline** — from my diploma right up to my future Masters plan
- **Leadership** — Google Student Ambassador section
- **Projects** — coming soon (actively building)
- **Contact** — LinkedIn, GitHub, and Gmail with a copy-to-clipboard button

Dark mode only. Age auto-calculates from my birthday so I never have to update it manually.

---

## Stack

Just the basics:

- HTML5
- CSS3 (custom properties, grid, flexbox, keyframe animations)
- Vanilla JavaScript (IntersectionObserver for scroll reveals, Canvas API for the particle background)
- Google Fonts — Space Grotesk, Inter, JetBrains Mono

No npm, no bundler, no dependencies.

---

## Folder structure

```
omkar-portfolio/
├── index.html
└── assets/
    ├── images/
    │   ├── omkar.png
    │   ├── gits-logo.png
    │   ├── niat-logo.png
    │   ├── bits-logo.png
    │   └── woolf-logo.png
    └── gifs/
        ├── code.gif
        ├── expert.gif
        └── learning.gif
```

CSS and JS are all inline in `index.html` — kept it that way intentionally since it's a single-page site and I didn't want to deal with relative path issues when opening locally.

---

## Running it locally

No setup needed. Just clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/NagillaOmkar/portfolio.git
cd portfolio
# open index.html in your browser
```

Or if you prefer a local server:

```bash
npx serve .
```

---

## Deploying

Works with any static host. I'm using GitHub Pages — just point it to the root of the repo and it picks up `index.html` automatically.

For Netlify or Vercel, drag and drop the folder and you're done.

---

## A few things I want to improve later

- Add actual project cards once I have things worth showing
- Maybe extract the CSS into a separate file at some point
- Add a dark/light toggle (low priority, honestly fine as dark-only for now)
- Better mobile experience for the floating pills in the hero

---

## Contact

- LinkedIn: [linkedin.com/in/n-omkar-vardhan](https://www.linkedin.com/in/n-omkar-vardhan)
- GitHub: [github.com/NagillaOmkar](https://github.com/NagillaOmkar)
- Email: nagilla.omkarvardhan@gmail.com
