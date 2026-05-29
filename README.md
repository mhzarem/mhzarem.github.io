# mhzarem.github.io

Personal academic website for Hossein Zaremehrjerdi.

**Live site:** https://mhzarem.github.io

## What you need to add before going live

### In `assets/`:
- **`profile.jpg`** — headshot, ideally square or 1:1 (the photo is shown in a circle, ~130px)
- **`CV.pdf`** — your latest CV

### In `assets/projects/` (project thumbnails — 16:10 ratio works well, ~280×200px):
- **`molfm.jpg`** — Multimodal molecular FM (could be a molecule render, a graph of conformer distribution, or a model architecture diagram)
- **`bioshield.jpg`** — Bio-Shield agentic biosecurity (LangGraph diagram, pest image, or system architecture)
- **`agreason.jpg`** — AgReason paper (figure from the paper or project page)
- **`cellpainting.jpg`** — Bayer Cell Painting (microscopy image or DINO feature map)
- **`desmoines.jpg`** — Des Moines property assessment (property photo, satellite, or system output)
- **`maizeear.jpg`** — MaizeEar-SAM (figure from the paper, ideally Figure 1 or a kernel-segmentation result)
- **`corteva.jpg`** — Corteva Text-to-SQL (UI screenshot or architecture diagram)

If any project image is missing, the site shows a clean placeholder ("image" pattern) — won't break.

### In `assets/logos/` (small institution/company logos, ~80×80px, square):
- **`isu.png`** — Iowa State University logo
- **`bayer.png`** — Bayer logo
- **`corteva.png`** — Corteva logo
- **`amirkabir.png`** — Amirkabir University logo

Missing logos hide gracefully.

## Deploy

1. Create a repo on GitHub named **exactly** `mhzarem.github.io`
2. Upload everything (drag the contents of this folder into the GitHub upload area)
3. Settings → Pages → Source: "Deploy from a branch" → `main` / `(root)` → Save
4. Visit https://mhzarem.github.io

## Update

Edit any file on github.com directly, commit, wait 30s — site updates automatically.

## Stack

- Plain HTML + CSS (no build step, no framework)
- Google Fonts: Inter (body), IBM Plex Mono (technical accents)
- Loads in &lt;0.5s
