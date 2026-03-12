# D&D Advisor 🐉

Real-time strategic guidance for Dungeons & Dragons gameplay. Import your character, set your game state, and get prioritized tactical suggestions.

**[Live Demo →](https://YOUR_USERNAME.github.io/dnd-advisor/)**

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g., `dnd-advisor`)
2. Upload `index.html` to the repository root
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**
7. Your site will be live at `https://YOUR_USERNAME.github.io/dnd-advisor/` within a few minutes

That's it — the entire app is a single HTML file with zero build step.

## Features

- **Import characters** from D&D Beyond JSON exports (drag & drop or paste)
- **Two demo characters** built in (Wizard and Fighter)
- **Interactive game state** — HP slider, spell slot pips, condition toggles, combat tracking
- **Four strategy profiles** — Safe, Aggressive, Balanced, and Chaos Mode
- **Prioritized suggestions** with confidence scores and reasoning
- **Mobile-first** responsive design with a dark fantasy theme
- **100% client-side** — no server, no database, no tracking

## How to Use Your Own Character

1. Go to [D&D Beyond](https://www.dndbeyond.com/) and open your character
2. Export the character as JSON (or use a browser extension like "Beyond20")
3. Drop the `.json` file onto the import zone, or paste the JSON directly

## Alternative Hosting

This works on any static file host:

| Service | How |
|---------|-----|
| **GitHub Pages** | Push `index.html` → Settings → Pages → Enable |
| **Netlify** | Drag the `index.html` file to [netlify.com/drop](https://app.netlify.com/drop) |
| **Vercel** | `npx vercel` in the folder |
| **Cloudflare Pages** | Connect your GitHub repo |
| **Local** | Just open `index.html` in any browser |
