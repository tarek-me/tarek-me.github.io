# Md. Tarekul Islam — Portfolio Website

A static personal portfolio site, styled like an engineering title-block /
blueprint drawing. No build step — just HTML, CSS, and vanilla JS.

## Files

```
index.html        — the whole site
style.css          — all styling
script.js          — lightbox + scroll animations
assets/            — all project photos and renders, organized by project
```

## How to put this online (GitHub Pages — free, same setup as ffathena.github.io)

1. **Create a GitHub account** if you don't have one, at github.com.

2. **Create a new repository** named exactly:
   ```
   <your-github-username>.github.io
   ```
   For example, if your GitHub username is `tarekul116378`, the repo must be
   named `tarekul116378.github.io` — this exact naming is what makes GitHub
   host it as a personal site automatically.

3. **Upload these files** into that repository:
   - On the repo page, click "Add file" → "Upload files"
   - Drag in `index.html`, `style.css`, `script.js`, and the whole `assets`
     folder (keep the folder structure intact)
   - Commit the changes

4. **Turn on GitHub Pages:**
   - Go to the repo's **Settings** tab → **Pages** (left sidebar)
   - Under "Source," choose the `main` branch and `/ (root)` folder
   - Click Save

5. **Wait 1–2 minutes**, then visit:
   ```
   https://<your-github-username>.github.io
   ```
   Your site will be live there — free, permanent, and easy to update any
   time by editing files directly on GitHub (or re-uploading).

## Editing later

- **Text**: open `index.html` in any text editor — every section is
  clearly commented (`<!-- ============ PROJECTS ============ -->` etc.)
- **Colors/fonts**: all in `style.css` under the `:root { ... }` block at
  the top — change one variable there and it updates everywhere
- **Photos**: replace files in `assets/` (keep the same filenames, or
  update the `src=` paths in `index.html` if you rename them)
- **New project**: copy one `<article class="project">...</article>`
  block in `index.html` and edit the content

## Still pending (from our conversation)

- Smart Cart real build photos (waiting on recovery from your brother's phone)
- Double Glazing Industries visit — exact date and whether solo/department/club
- Heat exchanger physical build — tube count and any measured thermal
  performance results, if you want to add them later
