# Handoff: Egglicious Sydney — One-Page Site → New GitHub Repo

## Overview
This is a finished, self-contained one-page marketing/ordering site for **Egglicious Sydney**, an Indian egg-specialty food truck in Blacktown, NSW. It's a client pitch demo built for the truck's owner. The goal of this handoff is purely operational: **create a new GitHub repository, push this site to it, and enable GitHub Pages** so it's viewable at a live URL.

## About the file
`index.html` is the **final, production-ready deliverable** — not a reference to recreate. It is a single self-contained HTML file (all fonts/scripts/styles inlined, works fully offline) built to be shipped as-is. Do not rewrite, "recreate in React," or restructure it — just host it.

## What to do
1. Init a git repo in this folder (or a fresh folder containing just `index.html`).
2. Create a new GitHub repository (suggested name: `egglicious-sydney-site` or similar — ask the user if they want a specific name/visibility).
3. Commit `index.html` as the repo's root file, named `index.html` (required for GitHub Pages to serve it at the domain root).
4. Push to the new repo's default branch.
5. Enable GitHub Pages for the repo (Settings → Pages → Deploy from branch → root), or use `gh` CLI / API to do so if scripting.
6. Report back the live Pages URL (typically `https://<username>.github.io/<repo-name>/`).

## Content notes
- All content (menu items, prices, hours, address, Instagram handle, Uber Eats link) comes from the truck's real business details — do not alter facts, only implementation.
- The gallery section intentionally uses styled placeholder tiles labeled "photo coming" — real food/truck photography will replace these later. No action needed here unless the user supplies real images.
- The truck's real logo (`assets/egglicious-logo.jpg` in the original project) is already inlined into `index.html` as a data URI — no separate asset file needed.

## Files
- `index.html` — the entire site (self-contained, offline-capable).
