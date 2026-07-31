# Nethra Vijayabaskar — Portfolio

A single-page portfolio site: `index.html`, `style.css`, `script.js`, and `resume.pdf`.
No build step, no dependencies — just static files.

## Deploy it (pick one)

### Option A — GitHub Pages (free, and it's already where your projects live)
1. Create a new repo on GitHub, e.g. `nethra-portfolio`.
2. Upload `index.html`, `style.css`, `script.js`, and `resume.pdf` to the repo root
   (drag-and-drop on github.com works, or use git from your machine).
3. Go to **Settings → Pages**.
4. Under **Source**, choose the `main` branch and `/ (root)` folder → **Save**.
5. Your site goes live at `https://<your-username>.github.io/nethra-portfolio/`
   within a minute or two.
6. Optional: add a custom domain under the same Pages settings if you buy one later.

### Option B — Netlify (free, drag-and-drop, fastest to set up)
1. Go to netlify.com and sign in (GitHub login works).
2. Drag the whole `portfolio` folder onto the Netlify dashboard ("Deploy manually").
3. Netlify gives you a live URL immediately, e.g. `nethra-vijayabaskar.netlify.app`.
4. You can rename the site (Site settings → Change site name) or connect a custom domain.

### Option C — Vercel (free, good if you want git-based auto-deploys)
1. Push the folder to a GitHub repo (same as Option A, steps 1–2).
2. Go to vercel.com → **Add New Project** → import that repo.
3. Leave the framework preset as "Other" (it's static HTML) and deploy.
4. Every future `git push` auto-redeploys.

## After it's live
- Put the link in your LinkedIn "Featured" section and at the top of your GitHub profile README.
- Add it to your résumé under your contact line.
- Update `resume.pdf` in this folder whenever your résumé changes, and redeploy —
  the "Résumé ↗" button always points to this file.

## Editing later
Everything is plain HTML/CSS in `index.html` / `style.css` — no framework, so you can
open it in any editor and change text, links, or colors directly. Section order:
Hero → About → Projects → Research → Skills → Achievements → Contact.
