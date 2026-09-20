# Nat Roberts Portfolio

A dependency-free static portfolio built with HTML, CSS, and a small amount of vanilla JavaScript. No Jekyll, npm, framework, or build step is required.

## Preview locally

The simplest option is to open `index.html` in your browser. For a closer approximation of GitHub Pages, run a local server from this folder, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a GitHub repository. For a personal site, name it `YOUR-USERNAME.github.io`. A normal repository name also works for a project site.
2. Upload the contents of this folder so `index.html` is at the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then save.
6. GitHub will display the public Pages address after deployment.

The site uses relative links, so it works both as a user site and as a project site.

## Before publishing

- Replace `replace-this-with-your-email@example.com` in `index.html` with your preferred public contact method.
- Add project screenshots/figures to `assets/images/` and link them from the project cards if desired.
- Add a résumé/CV to `assets/documents/` and create a link in the navigation or hero.
- Add GitHub/LinkedIn links if desired.
- For a working contact form on a static site, use a static form provider or link directly to email. GitHub Pages does not process server-side form submissions itself.

## Structure

- `index.html` — home/about/featured work/skills/education/contact
- `projects.html` — expanded project case studies
- `research.html` — publications and presentations
- `css/style.css` — all visual styling
- `js/main.js` — mobile navigation and copyright year
- `assets/` — images and documents

## Images and project organization

This version includes original SVG visuals for all three featured projects, so the site is publishable without external image hosting. See `IMAGE_GUIDE.md` for exact filenames, recommended dimensions, replacement instructions, and the consulting-style case-study structure.

The project hierarchy is now:

- Home page: concise project cards + one key result
- Projects page: numbered case studies with context, role, methods, results, takeaway, visual, and tool tags
- Research page: scholarship and conference dissemination

This separation keeps the home page executive-level while allowing hiring managers, collaborators, or consulting clients to inspect technical depth on the Projects page.
