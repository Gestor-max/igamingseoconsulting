# iGaming SEO Consulting

Static site for Nestor Vazquez — iGaming SEO consulting.

- **Local folder:** `C:\Users\Floki\igamingseoconsulting`
- **GitHub:** https://github.com/Gestor-max/igamingseoconsulting
- **Hosting:** Cloudflare Pages (no build step — plain HTML/CSS/JS, output directory = project root)

## Structure

```
index.html    # single-page site (services, experience, speaking, about, contact)
styles.css    # dark theme, responsive
script.js     # mobile nav toggle
```

## Deploy

Direct upload (no git connection):

```bash
wrangler pages deploy . --project-name igamingseoconsulting
```

Or push to `main` if the Pages project is connected to the GitHub repo
(connect it in the Cloudflare dashboard → Workers & Pages → Settings → Build).
