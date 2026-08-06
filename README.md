# Shanyu Chauhan — Portfolio Site

Static site, no build step. Deployable to GitHub Pages in ~10 minutes.

## Deploy to GitHub Pages

1. Create a new **public** repo named exactly `YOUR-USERNAME.github.io`
   (e.g., `shanyuchauhan.github.io`). This makes the site live at
   `https://YOUR-USERNAME.github.io` with no extra config.
2. Upload everything in this folder to the repo root (drag-and-drop on
   github.com works, or `git init` → `git add .` → `git commit` → `git push`).
3. Wait ~2 minutes. Your site is live.
4. Update your resume's portfolio line to the new URL.

Optional custom domain (`shanyuchauhan.com`, ~$10/yr via Namecheap/Porkbun):
repo → Settings → Pages → Custom domain, then add the DNS records GitHub
shows you.

## Before you publish — checklist

- [ ] Replace every dashed orange placeholder box. Each one names the exact
      file to add (e.g., `images/beed-hero.jpg`) — drop the file into
      `images/` and swap the placeholder `<div class="ph">…</div>` for the
      `<img>`/`<video>` tag shown in the HTML comment directly above it.
- [ ] Fill every `[bracketed]` text placeholder — same convention as your
      resume.
- [ ] Put your resume PDF at `assets/Shanyu_Chauhan_Resume.pdf` (path is
      already linked from every page).
- [ ] Replace `YOUR-USERNAME` in the GitHub links (index.html, beed.html).
- [ ] BEED demo video: 20–30 s, phone is fine, good light, show it working.
      Compress to under ~15 MB (export at 720p) so pages load fast.
- [ ] Rocket footage: confirm with RPL what's OK to post publicly,
      especially staging-mechanism details and propellant specifics.
- [ ] Nothing from Bayer/Vividion beyond what's on your resume — no
      screenshots, data, or internal tool names.
- [ ] Test on your phone after deploying. Recruiters open portfolios on
      phones.

## Files

```
index.html              Homepage: hero, spec strip, project index, about
projects/beed.html      BEED (flagship)
projects/rockets.html   Staged rockets — UCSD RPL
projects/speech.html    TACL research
projects/robotics.html  RoboMaster robot
css/style.css           All styling (edit tokens at the top to retheme)
images/                 Drop photos/videos here (filenames listed in pages)
assets/                 Resume PDF goes here
```

## Editing tips

- All colors/fonts live in the `:root` block at the top of `css/style.css`.
- To add a project later: copy any `projects/*.html`, edit the content, and
  add a card to the grid in `index.html`.
- Keep the "Currently:" line on the homepage fresh — it's one line and makes
  the site look alive.
