# Nat Roberts Portfolio

A dependency-free static portfolio built with HTML, CSS, and a small amount of vanilla JavaScript. No Jekyll, npm, framework, or build step is required.

## Preview locally

The simplest option is to open `index.html` in your browser. For a closer approximation of GitHub Pages, run a local server from this folder, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.


## Structure

- `index.html` — home/about/featured work/skills/education/contact
- `projects.html` — expanded project case studies
- `research.html` — publications and presentations
- `css/style.css` — all visual styling
- `js/main.js` — mobile navigation and copyright year
- `assets/` — images and documents


The project hierarchy is now:

- Home page: concise project cards + one key result
- Projects page: numbered case studies with context, role, methods, results, takeaway, visual, and tool tags
- Research page: scholarship and conference dissemination

This separation keeps the home page executive-level while allowing hiring managers, collaborators, or consulting clients to inspect technical depth on the Projects page.
