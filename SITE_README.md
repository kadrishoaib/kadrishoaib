# Shoaib — GitHub Pages Portfolio

Innovative Solutions Architect | Vice President | 15+ Years

This repo contains:
- `index.html` – full single-file GitHub Pages portfolio (no build step, inline CSS)
- `PROFILE_README.md` – copy-paste GitHub Profile README (`github.com/<username>/<username>`)

## Quick deploy – GitHub Pages

1. Create repo: `yourusername.github.io`
   OR use any repo → Settings → Pages

2. Push files:
```
git init
git add index.html
git commit -m "feat: Shoaib portfolio v1"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

3. Enable Pages:
Settings → Pages → Source: Deploy from a branch → main → / (root)

Site live at: `https://yourusername.github.io`

## Customize in 60 seconds

Edit `index.html` – search/replace these tokens:
- `shoaib` → your GitHub handle (5 places)
- `shoaibkadri@ymail.com` → your email (3 places)
- `linkedin.com/in/shoaib-kadri-418b0519` → your LinkedIn
- Hero stats: 15+, 120+, 8, 40% – update to yours
- Projects: 4 featured cards in `#projects` – swap copy
- Location: `Mumbai, India`

Colors:
`:root` in `<style>`:
--accent:#32d6a0
--accent-2:#61a8ff

Fonts are Google Fonts: Fraunces + Inter + JetBrains Mono.

## GitHub Profile README

1. Create a new repo named EXACTLY your username.
   e.g. `github.com/kadrishoaib/kadrishoaib`
2. Add `PROFILE_README.md` as `README.md`
3. Update stats image URLs: replace `username=shoaib` → your handle
4. Pin 4 repos:
   - Ops-Copilot
   - routing-mesh
   - automation-hub
   - document-ai-factory

Optional snake commit graph:
https://github.com/Platane/snk

## Files

- index.html – portfolio site
- PROFILE_README.md – profile README
- README.md – same as profile (for repo root)
- 404.html – nice 404
- .nojekyll – disables Jekyll processing

MIT – do what you want with it.
