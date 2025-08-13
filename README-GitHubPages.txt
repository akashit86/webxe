
# WebXE — Static Site (GitHub Pages Ready)

Upload to a public GitHub repository. Enable Pages on the `main` branch (root).
Keep the `CNAME` file to bind the custom domain `webxe.in`.

## Custom Domain Steps (Quick)
1. Push this folder to a public repo (e.g., `webxe-site`).
2. Settings → Pages → Build and deployment: Source = Deploy from a branch. Branch = `main` / root.
3. Under "Custom domain", enter `webxe.in`. Save.
4. In your DNS panel, create/verify:
   - `A` records to GitHub Pages: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `AAAA` records (optional IPv6): 2606:50c0:8000::153, ::154, ::155, ::156
   - Or a `CNAME` for subdomains to `<your-username>.github.io`.
5. Wait for DNS to propagate, then enforce HTTPS.

## Monetization
- Find `<!-- AD / AFFILIATE -->` comments to paste AdSense/affiliate code.
- Edit blog posts to add relevant affiliate links.
