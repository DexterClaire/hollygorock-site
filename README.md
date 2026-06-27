# hollygorock-site

Personal site for [hollygorock.com](https://hollygorock.com). Built with [Astro](https://astro.build) and deployed to GitHub Pages.

## Local dev

```bash
npm install
npm run dev
```

## Deploy

Push to `main`. The GitHub Actions workflow builds and deploys automatically.

## DNS setup (one-time)

At your domain registrar, point `hollygorock.com` to GitHub Pages:

**A records (apex domain):**
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**CNAME (www):**
```
www → dexterclaire.github.io
```

In GitHub repo Settings → Pages → Custom domain, enter `hollygorock.com` and enable Enforce HTTPS.
