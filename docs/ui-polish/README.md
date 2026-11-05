# UI polish review artifacts

Native-size browser screenshots of the static site, with overlapping viewports:

- Desktop, 1280 × 900: [hero](desktop-1.png), [origin and approach](desktop-2.png), [approach and closing](desktop-3.png).
- Mobile, 390 × 844 at device pixel ratio 2: [hero](mobile-1.png), [origin](mobile-2.png), [approach](mobile-3.png), [closing and footer](mobile-4.png).

These are rendered site screenshots, not mockups. The arch is conceptual artwork,
not a product screen. Screenshot crops intentionally overlap so every section
can be reviewed at a readable scale.

## Validation

- Browser overflow checks at 320, 390, 768, 1280, and 1920 CSS pixels: no horizontal overflow.
- Actual link activation: Discover Arca → `#arca`; Approach → `#approach`; Back to top → `#top`.
- Keyboard: initial Tab reveals the skip link with a visible outline; Enter navigates to `#main`; next Tab reaches the main CTA, bypassing header navigation.
- axe-core 4.10.3, WCAG A/AA/2.1 AA and best-practice rules: zero violations, 36 passing rules. Two symbol-only arrow contrast checks required manual review; their foreground/background ratio is 12.18:1.
- Text color pairings: 4.96:1 minimum among the primary and muted text combinations. This is targeted contrast verification, not a claim of complete accessibility certification.
- All local assets and fragment destinations exist; IDs are unique.
- Formatting and `git diff --check` pass.
- Stylesheet optimization preserved the computed-style fingerprint of every element at all five checked widths.

No application build step or runtime JavaScript is needed. The temporary audit
script was removed after the browser check and is not part of the site.
