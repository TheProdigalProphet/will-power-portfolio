# Forma DJR Deck (hero title font)

The portfolio hero uses **Forma DJR Deck Italic** (weight 400 — not bold).

This is a commercial typeface by [DJR](https://djr.com/forma). It is **not** free to redistribute without a license.

## Add the webfont files (required for GitHub Pages visitors)

1. License **Forma DJR Deck** for web/self-hosting from DJR or Adobe Fonts / Type Network.
2. Export or download the **Italic** (Regular/400) web files.
3. Place them in this folder using one of these names:

```
fonts/FormaDJRDeck-Italic.woff2   ← preferred
fonts/FormaDJRDeck-Italic.woff
fonts/FormaDJRDeck-Italic.otf
fonts/FormaDJRDeck-Italic.ttf
```

4. Commit and push. The site already has `@font-face` wired to these paths.

## Without the files

- Machines that have Forma DJR Deck installed (e.g. desktop design tools) will still render it.
- Everyone else falls back to **Switzer** italic (Fontshare free neo-grotesque), then system sans.
