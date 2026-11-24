# Developer Portfolio

Static, dependency-free portfolio: mobile-first (Flexbox + CSS Grid), dark/light theme toggle (remembers choice, respects system setting), smooth-scroll navigation with active-section highlighting.

## Customize
1. `index.html`: replace "Your Name", `you@example.com`, the GitHub/LinkedIn links, about text, skills, projects and resume entries.
2. Add your `resume.pdf` next to `index.html` (the Download button points to it).
3. `styles.css`: change colors at the top (`--accent`, etc.).

Preview locally: open `index.html`, or run `npx serve .`

## Deploy (pick one, all free)

### GitHub Pages
```bash
git init && git add . && git commit -m "Portfolio"
git branch -M main
git remote add origin https://github.com/<you>/<you>.github.io.git   # or any repo name
git push -u origin main
```
Then on GitHub: **Settings → Pages → Deploy from a branch → main / (root)**. Live at `https://<you>.github.io/` (or `/<repo>/`).

### Netlify
Drag the folder onto https://app.netlify.com/drop, or connect the GitHub repo (build command: none, publish directory: `.`).

### Vercel
Import the GitHub repo at https://vercel.com/new (Framework: Other, no build command), or run `npx vercel --prod` in this folder.
