# Portfolio — Nguyen Duc Long

A single-page portfolio for a backend engineer.
Built with vanilla HTML, CSS, and JavaScript — no framework, no build step.

**Live →** https://duclong565.github.io/portfolio/

---

## Stack

- HTML / CSS / JavaScript (vanilla, single file)
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) — monospace typography
- No bundler, no dependencies, no runtime

## Design

- **Press** theme — neutral white background with newspaper red accent
- IDE-inspired layout: section headers like `// 02 / work`, key/value blocks, `>` quote prefixes
- VS Code-style status bar (sticky bottom) with live scroll progress
- Subtle dot-grid background and 80-char IDE column rule on the right
- Mobile-first responsive, reduced-motion friendly

## Structure

```
portfolio/
├── index.html      single-file portfolio
├── portrait.png    hero photo
└── README.md
```

## Run locally

Any static server works:

```bash
python3 -m http.server 8000
# or
npx serve .
```

Then open <http://localhost:8000>.

## Deploy

Already wired for GitHub Pages from the `main` branch (root).
Any static host works too — drop into Vercel, Netlify, Cloudflare Pages.

## Contact

- Email — [longnguyen.sitde@gmail.com](mailto:longnguyen.sitde@gmail.com)
- LinkedIn — [lavender565](https://www.linkedin.com/in/lavender565/)
- GitHub — [duclong565](https://github.com/duclong565)

---

Hanoi · MMXXVI
