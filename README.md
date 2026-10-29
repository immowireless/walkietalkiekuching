# walkietalkiekuching.com

Static site (no build step) for GitHub Pages.

## Publish
1. Create a GitHub repo (e.g. `walkietalkiekuching`) and upload every file in this folder to the root (including `CNAME` and `.nojekyll`).
2. Repo > Settings > Pages > Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`.
3. Custom domain: `www.walkietalkiekuching.com`, then tick "Enforce HTTPS" once it becomes available.

## DNS (at your domain registrar)
- `CNAME`  host `www`  ->  `<your-github-username>.github.io`
- So the bare domain also works, add four `A` records on host `@`:
  185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
  (and set up a redirect from the bare domain to www if your registrar offers one)

## Edit
Contact number, address and WhatsApp link are in `index.html` (search `60102835120`).
