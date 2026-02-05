# Selinger Apps Website

Company website for Selinger Apps, hosted on GitHub Pages at [selingerapps.com](https://selingerapps.com).

## Status

**Live** — Deployed February 2026 with HTTPS enabled.

## Structure

```
├── index.html      # Main landing page
├── privacy.html    # Privacy Policy
├── impressum.html  # Legal Notice (German)
├── CNAME           # Custom domain configuration
└── README.md       # This file
```

## Tech Stack

- Plain HTML with [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Inter](https://fonts.google.com/specimen/Inter) font via Google Fonts
- Hosted on [GitHub Pages](https://pages.github.com/)

## Local Development

Simply open `index.html` in a browser. No build step required.

For live reload during development, you can use any local server:

```bash
# Python
python3 -m http.server 8000

# Node.js (npx)
npx serve
```

## Deployment

The site automatically deploys when pushing to the `main` branch.

### DNS Configuration (Namecheap)

**A Records (apex domain):**
```
@ → 185.199.108.153
@ → 185.199.109.153
@ → 185.199.110.153
@ → 185.199.111.153
```

**CNAME Record (www subdomain):**
```
www → oliver-selinger.github.io
```

## Contact

Oliver Selinger-Lutz
[oliver@selingerapps.com](mailto:oliver@selingerapps.com)
