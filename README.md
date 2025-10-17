# XIAOMINZ · 新西兰笑谜网

A minimal, static landing page for **xiaominz.com** (NZ edition of XIAOMIAUS).

- Same layout as AU site, with **50 new jokes + 30 new riddles**.
- Footer contains a link back to the Australia site.
- No external deps; works on GitHub Pages or any static hosting.

## Quick Deploy (GitHub Pages)
1. Create a repo `xiaominz.com` (or `xiaominz-site`).
2. Add `index.html` from this package and commit to `main`.
3. Settings → Pages → Deploy from a branch (main / root).
4. Add custom domain `xiaominz.com`, enable **Enforce HTTPS**.
5. DNS at your registrar:
   - A @ → 185.199.108.153 / 109.153 / 110.153 / 111.153
   - CNAME www → `<your-username>.github.io`

## Notes
- Contact email: `xu456xu@gmail.com`
- Update jokes/riddles directly inside the `<script>` block if needed.

Generated 2025-10-17.
