# AI Build — Fixed Base for GitHub Pages

This build **forces** `base = /aibuild/` whenever the site runs on `*.github.io`. That prevents broken CSS/JS paths on a project site.

### How to use
1. Copy these files into your repo **root** (keep `_assets` next to your HTML files).
2. Commit & push.
3. GitHub Pages → Settings → Pages → Deploy from `main` (root).
4. Your site will load CSS/JS at `https://otiseduncan.github.io/aibuild/` reliably.

If you later rename the repo, change `/aibuild/` in the inline `<script>` near the top of each HTML file.
© 2025 Your Company
