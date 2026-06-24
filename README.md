# Aditi Shinde — PM Portfolio (static site)

A complete, ready-to-deploy portfolio website. No build step, no dependencies — just static HTML/CSS.

## Files
- `index.html` — Home (hero, stats, intro)
- `about.html` — About, how I work, credentials
- `projects.html` — Projects grid (2 case studies)
- `fundflow.html` — FundFlow case study
- `navbharat.html` — NavBharat case study
- `contact.html` — Contact details + resume download
- `styles.css` — all styling
- `resume.pdf` — your resume (already copied in)

## Before you deploy — 2 quick edits
1. **LinkedIn link:** search all files for `REPLACE-ME` and replace with your real LinkedIn URL.
   (It appears in the nav/footer/contact of each page.)
2. **(Optional) Case-study images:** export your wireframe/WBS/risk slides as PNGs, drop them in this
   folder, and add `<img src="yourimage.png" alt="...">` inside the relevant case-study page.

## Preview locally (optional)
Just double-click `index.html` — it opens in your browser. Everything works offline.

## Deploy to Vercel (free) — pick ONE method

### Method A — Drag & drop (easiest, no account setup hassle)
1. Go to **vercel.com** → sign up (free, use GitHub/Google/email).
2. On the dashboard, look for **"Add New… → Project"**, or use **vercel.com/new**.
3. If drag-and-drop isn't offered directly, use the CLI method below — it's the most reliable for a plain folder.

### Method B — Vercel CLI (most reliable for a static folder)
1. Install Node.js if you don't have it (nodejs.org).
2. In Terminal:
   ```
   npm i -g vercel
   cd "/Users/aditishinde/Desktop/portfolio-site"
   vercel
   ```
3. Follow the prompts (log in, accept defaults, "no" to linking an existing project).
4. Vercel gives you a live URL like `https://portfolio-site-xxxx.vercel.app`.
5. Run `vercel --prod` to push the production version.

### Method C — GitHub + Vercel (best for ongoing edits)
1. Create a GitHub repo, upload this folder's files.
2. In Vercel: **Add New → Project → Import** your repo.
3. Framework preset: **Other** (it's static). Deploy.
4. Every time you push to GitHub, Vercel auto-redeploys.

## Custom domain (optional)
In Vercel project → **Settings → Domains** → add `aditishinde.com` (buy via Vercel or connect one you own).
