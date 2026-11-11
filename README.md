# statera-labs.com

The Statera Labs teaser for Arca, served by GitHub Pages from `main` at the
repository root. Static HTML and CSS: no build step, scripts, tracking or
external requests. Open `index.html` directly to preview; keep `styles.css` and
`assets/` beside it.

## Direction and copy

Arca's own palette: parchment, ink and terracotta, with oxblood sealing wax used
only in the Arca mark. Self-hosted type: Newsreader for headings (as in Arca
itself) and Hanken Grotesk for text; font licenses are in `assets/`. The
Newsreader italic is a Latin subset fixed at weight 400 and display size,
because it sets only a headline word. Statera Labs' mark is a steelyard (*statera*); Arca's is a sealed
chest (*arca*) with an arch on its face, drawn inline as SVG. The principle
symbols are arches expressing a common ground for counsel and clients. Nothing
is loaded from an outside service at runtime. The page has three numbered
sections: the founding perspectives, our approach, and development status.

Company: **Statera Labs**. Product: **Arca**. Lead line: **Good counsel. Clearer ground.** Positioning: legal case management for small practices, designed
around counsel and clients. The copy hints at intent without promising planned
behavior, a launch date, pricing, customers, certifications or a demo. There is
no signup and nothing is collected.

The origin story reflects the founder’s account: their attorney found existing
legal tools disconnected and misaligned with the work; as a client and software
engineer, the founder saw complex tasks left unsupported by modern tooling and
AI. This is a founding perspective, not a customer testimonial or product claim.

After the entity is formed, change the footer to **© 2026 Statera Labs LLC**.

## Domain

`CNAME` sets the custom domain to `statera-labs.com`. At the registrar:

- apex `A` records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`,
  `185.199.111.153` (and `AAAA` `2606:50c0:8000::153` … `8003::153` for IPv6)
- `www` `CNAME` → `stateralabscom.github.io`

Then turn on **Enforce HTTPS** in the repository's Pages settings once the
certificate is issued.
