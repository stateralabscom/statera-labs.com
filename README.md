# statera-labs.com

The Statera Labs teaser for Arca, served by GitHub Pages from `main` at the
repository root. Static HTML and CSS: no build step, scripts, tracking or
external requests. Open `index.html` directly to preview; keep `styles.css` and
`assets/` beside it.

## Direction and copy

Warm parchment, terracotta, generous space, Newsreader headings and Hanken
Grotesk body copy (fonts self-hosted under the OFL; licenses in `assets/`). The
stacked sheets are a conceptual illustration, not a product screenshot or final
logo.

Company: **Statera Labs**. Product: **Arca**. Lead line: **Good counsel. Clearer
ground.** Positioning: legal case management for small practices, designed
around counsel and clients. The copy hints at intent without promising planned
behavior, a launch date, pricing, customers, certifications or a demo. There is
no signup and nothing is collected.

After the entity is formed, change the footer to **© 2026 Statera Labs LLC**.

## Domain

`CNAME` sets the custom domain to `statera-labs.com`. At the registrar:

- apex `A` records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`,
  `185.199.111.153` (and `AAAA` `2606:50c0:8000::153` … `8003::153` for IPv6)
- `www` `CNAME` → `stateralabscom.github.io`

Then turn on **Enforce HTTPS** in the repository's Pages settings once the
certificate is issued.
