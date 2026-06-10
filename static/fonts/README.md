# /fonts/

Self-hosted web fonts for rrows.net, served at `https://rrows.net/fonts/` via this Micro.blog static-pages plugin (the plugin's `static/` folder maps to the site root).

## Literata (subset: latin, from google-webfonts-helper)

Drop these five woff2 files here, then bump the plugin version, push, and update the plugin in Micro.blog:

- `literata-v40-latin-regular.woff2`   — 400 normal
- `literata-v40-latin-italic.woff2`    — 400 italic
- `literata-v40-latin-500.woff2`       — 500 normal (nav)
- `literata-v40-latin-600.woff2`       — 600 normal
- `literata-v40-latin-600italic.woff2` — 600 italic

These are referenced by `@font-face` in the site `custom.css` (Palim reading skin), replacing the Google Fonts `@import`.
