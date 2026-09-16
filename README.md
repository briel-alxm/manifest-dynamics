# Manifest Dynamics

**Structural Integrity for the Substrate**  
A structural theory of value emergence and stabilization · Wendy Briel · BrielOS · 2026

Live site: [manifestdynamics.org](https://www.manifestdynamics.org/)

---

## What this is

Manifest Dynamics is a framework for understanding how value emerges through interaction, how it moves through systems, and how it loses or preserves its connection to the people and conditions that created it.

Core question: **What happens to value after it is created?**

This repository hosts the public site for the framework — a reader-friendly entry point into the ideas, with a path into the formal working paper layer.

---

## Repo structure

```
manifest-dynamics/
├── index.html      # Main site (static, single-page)
└── README.md       # This file
```

- Pure static HTML/CSS (no build step).
- Designed to deploy cleanly on Vercel, GitHub Pages, Netlify, or any static host.

---

## Local preview

Open `index.html` in a browser, or serve it:

```bash
# Python
python -m http.server 8000

# Node (if you have npx)
npx serve .
```

Then visit `http://localhost:8000`.

---

## Deploy notes

### Vercel
- Connect this repo (or push to `main`).
- Framework preset: Other / static.
- Output: root (no build command needed).
- Custom domain: `manifestdynamics.org` (and `www`).

### GitHub Pages
- Settings → Pages → Deploy from branch `main` / root.

---

## Framework at a glance

| Condition        | Role                                      |
|------------------|-------------------------------------------|
| Origin           | Where insight / intention begins          |
| Agency           | Capacity to move origin into expression   |
| Friction         | Forces that resist or distort movement    |
| Closure          | What reconnects expression to its origin  |
| Attribution Lag  | Delay between use and recognition of source |

**Failure state:** Foundational Insight Orphaning — the idea survives, the source disappears.

**Axiom:** *Attribution precedes scale. A system only achieves true coherence when authorship remains traceable across every level of the substrate.*

---

## Staying organized

- Keep the public site simple: one `index.html` for the framework landing page.
- Formal paper content can live as a separate page, PDF, or linked resource when ready.
- Prefer clear section anchors (`#start`, `#framework`, `#concepts`, `#paper`) so the page stays navigable.
- Update the README when you add files, change deploy settings, or introduce a formal notation companion.

---

## Attribution

Manifest Dynamics · Wendy Briel · BrielOS · 2026  
Site & framework presentation maintained in this repository.
