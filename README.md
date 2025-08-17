# AI Build — 5‑Page Dark Theme Starter

A production‑ready, mobile‑first, SEO‑primed template. Dark, neutral palette with a polished feel.

## Pages
- `index.html` (Home)
- `about.html`
- `services.html`
- `portfolio.html`
- `contact.html`

## Features
- Works locally **and** on GitHub Pages (root or `/REPO/`) via dynamic `<base>` injection
- Accessible, keyboard‑friendly navigation (mobile hamburger)
- Full meta tagging (OG + Twitter) and JSON‑LD schema
- Clear, labeled content slots: look for `[[...]]` comments
- Placeholder images in `_assets/img/` sized for hero, sections, and OG

## Replace Content (dummy‑proof guide)
1. **Branding:** In the header, change `[[YOUR BRAND]]`. Update footer company fields.
2. **Images:** Drop your images into `_assets/img/` and update filenames in inline `style="--hero:url(...)"` and `--bg:url(...)` comments. Recommended sizes are shown next to each slot.
3. **Text:** Replace every `[[ ... ]]` token with real copy.
4. **SEO:** In each page `<head>` update:
   - `<meta name="description">`
   - `keywords`, `author`, and `canonical`
   - Open Graph + Twitter `title/description/url/image`
   - JSON‑LD fields: site name, URLs, company info
5. **Contact form:** Works with Netlify (`data-netlify="true"`). For other providers, wire up your action endpoint.

## GitHub Pages
- **Project site:** Settings → Pages → Deploy from `main`, root or `/docs`. This template works in either location.
- If you move files into `/docs`, move the **entire** folder structure unchanged.

## Local Preview
Use any static server (Python example):
```bash
cd ai-build-template
python3 -m http.server 3000
# open http://localhost:3000
```

## Customize Theme
Edit `_assets/css/global.css` variables under `:root` for colors, radius, and shadows.

© 2025 Your Company
