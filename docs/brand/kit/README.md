# Brand kit

Statera Labs and Arca marks for other sites, profiles and chat apps. Every PNG
and JPG is rendered from the SVG of the same name in `svg/`; edit the SVG and
re-render rather than editing a raster.

Colours: paper `#f6f1e9`, ink `#2c2722`, terracotta `#a24d2d`, cream `#fff7ee`.
Oxblood `#6e1f2b` is the Arca seal only.

## Which file to use

| Need | File |
| --- | --- |
| Profile picture or avatar (Slack, GitHub, LinkedIn, X, Google) | `statera-avatar-terracotta` (default), `-paper`, or `-ink`. Square, full bleed, safe inside a circle crop. |
| Mark on a light page or document | `statera-mark-ink` or `statera-mark-terracotta` |
| Mark on a dark page | `statera-mark-cream` |
| Browser tab, app icon | `statera-favicon` (16 to 512 px; 180 is the Apple touch icon) |
| Arca, the product | `arca-mark`, or `arca-mark-on-terracotta` on its tile |

Prefer SVG where a site accepts it. Use PNG (transparent) when it doesn't, and
JPG only where transparency is refused; the JPGs are 1024 px squares with the
mark centred on a solid ground.

## Files

- `svg/`: the source of every mark.
- `png/<name>-<width>.png`: transparent, at the widths listed in the folder.
- `jpg/<name>.jpg`: 1024 × 1024.

The Statera marks are trimmed tight to the drawing; leave clear space of at
least the hook's diameter around them. The avatars use the heavier favicon
strokes so the glass still reads at 32 px.
