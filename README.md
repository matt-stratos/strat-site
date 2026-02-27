# Stratos Composites — Landing Page

Static landing page for [stratoscomposites.com](https://stratoscomposites.com). Built with plain HTML5 and CSS3, hosted on Cloudflare Pages.

---

## Project Structure

```
stratos-composites-site/
├── index.html       # Single-page site
├── style.css        # All styles
├── assets/
│   └── logo.svg    # logo
└── README.md
```

---

## Local Development

No build step or local server required. Open `index.html` directly in any browser to preview changes before committing.

---

## Deployment

Pushes to the `main` branch trigger an automatic redeploy on Cloudflare Pages. No manual action needed.

---

## Expanding the Site

When the site grows beyond a single page, we can migrate to **Astro** as it supports the same plain HTML/CSS authoring style with the option to introduce components and content collections incrementally, without a full rewrite.