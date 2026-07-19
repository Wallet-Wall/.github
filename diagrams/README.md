# Adaptive Mermaid diagrams

The organization profile publishes each diagram as transparent light and dark SVG
variants selected with `prefers-color-scheme`. Editable Mermaid sources live in
`diagrams/adaptive/`, and `diagrams/adaptive-manifest.json` maps each source to its
Markdown page and rendered assets.

When a diagram changes:

1. Update its `.mmd` source without changing the public/private boundary language.
2. Render both variants with Mermaid 11 and the WalletWall light/dark palettes.
3. Keep both SVG roots transparent and script-free.
4. Load both files as browser images at desktop and narrow/mobile widths.
5. Treat parse errors, broken images, clipping, low contrast, or console errors as
   blockers.

Do not edit an SVG without making the same semantic update in its `.mmd` source.
