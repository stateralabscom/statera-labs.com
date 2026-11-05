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
- axe-core 4.14.0, WCAG A/AA/2.1 AA and best-practice rules: zero violations, 32 passing rules. Symbol-only arrows and the status over the image required manual contrast review; arrow contrast is 12.18:1 and secondary text over the image’s top region exceeds 9.58:1.
- Text color pairings: 4.96:1 minimum among the primary and muted text combinations. This is targeted contrast verification, not a claim of complete accessibility certification.
- All local assets and fragment destinations exist; IDs are unique.
- Formatting and `git diff --check` pass.
- Stylesheet optimization preserved the computed-style fingerprint of every element at all five checked widths.

No application build step or runtime JavaScript is needed. The temporary audit
script was removed after the browser check and is not part of the site.

## Independent agent council

Three reviewers assessed desktop/mobile screenshots from separate initial
contexts without receiving the desired passing score. They reviewed successive
revisions, compared a separate serif/dark art-direction study, and discussed
their final rubrics while retaining independent ratings.

| Reviewer | Final score | Assessment                                                                            |
| -------- | ----------- | ------------------------------------------------------------------------------------- |
| UX       | 9.0 / 10    | Excellent clarity, reading hierarchy, and prelaunch framing.                          |
| Visual   | 9.0 / 10    | Strong composition and identity; originality is strong rather than category-defining. |
| Brand    | 8.8 / 10    | Polished and recognizable; more weight reserved for exceptional, ownable expression.  |

The latest retained refinement uses custom generated conceptual artwork of layered
arches. The image is a locally served 44 KB WebP, not a product screen. A compact
mobile composition preserves reading pace. The founder origin retains separate
attorney and client/software-engineer perspectives. All seven refreshed screenshots
were independently reviewed by the original council.

All three recommend retaining the revision and report no material visible issue.
The brand reviewer still reserves a higher score for greater distinctiveness.
The full goal remains open. These are agent assessments, not external user research.
