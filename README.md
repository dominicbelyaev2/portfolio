# Dominic Belyaev — Portfolio

Personal engineering portfolio. Built on the free [MyPortfolio](https://bootstrapmade.com/myportfolio-bootstrap-portfolio-website-template/) template from BootstrapMade (same template Hannah Huang's portfolio uses) — plain HTML/CSS/JS, no build step.

## Preview locally
Just open `index.html` in a browser.

## Deploy to GitHub Pages (free)
1. Create a GitHub account (if needed) and a new **public** repo named `portfolio`.
2. In this folder:
   ```
   git init
   git add .
   git commit -m "Portfolio V1"
   git branch -M main
   git remote add origin https://github.com/<username>/portfolio.git
   git push -u origin main
   ```
3. On GitHub: repo **Settings → Pages → Source: Deploy from a branch → main / (root)**.
4. Site goes live at `https://<username>.github.io/portfolio/` within a minute or two.

## Custom domain (dominicbelyaev.com — already purchased)
1. At the registrar, add DNS records: four `A` records on `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`, and a `CNAME` on `www` → `<username>.github.io`.
2. GitHub repo **Settings → Pages → Custom domain** → `dominicbelyaev.com` → Save (commits a `CNAME` file).
3. Check **Enforce HTTPS** once the cert is issued (minutes to ~24 h).
4. Verify the domain in GitHub account settings (Settings → Pages → verified domains) to protect it.

## TODOs before going live
- [ ] Replace placeholder SVGs in `assets/img/projects/` with real photos (keep the same filenames, or update the `<img>` tags)
- [ ] Add `assets/resume.pdf` (linked from the hero)
- [ ] Update both LinkedIn links in `index.html` with the real profile URL
- [ ] Verify the FSAE ~30% mass-reduction figure (see TODO comment in `pedalbox.html`)
- [ ] Levanta section is intentionally generic — do **not** add technical detail without written permission (ITAR)
- [ ] Replace `assets/img/favicon.png` / `apple-touch-icon.png` with your own
- [ ] Keep the "Designed by BootstrapMade" footer credit (free-license requirement) or buy a license to remove it
