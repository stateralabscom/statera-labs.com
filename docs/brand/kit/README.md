# Statera Labs brand kit

Ready-made files for profiles, chat apps, link previews, email and other
sites. Every raster is rendered from an SVG in this folder; change the SVG and
re-render rather than editing a PNG.

Colours: paper `#f6f1e9`, ink `#2c2722`, terracotta `#a24d2d`, cream `#fff7ee`.
Type: Newsreader for headlines, Hanken Grotesk for text (`assets/`). Oxblood
`#6e1f2b` is the Arca seal only.

## Where each file goes

| Place | File | Size |
| --- | --- | --- |
| Slack workspace icon, Slack/Teams/Discord profile | `avatar/statera-avatar-terracotta-512.png` | 512 × 512 |
| GitHub org, Google Workspace, Zoom | `avatar/statera-avatar-terracotta-512.png` | 512 × 512 |
| LinkedIn page logo, X profile | `avatar/statera-avatar-terracotta-400.png` | 400 × 400 |
| YouTube, Facebook, anything asking for "at least 800" | `avatar/statera-avatar-terracotta-800.png` | 800 × 800 |
| A site that refuses PNG | `avatar/statera-avatar-*-1024.jpg` | 1024 × 1024 |
| Link previews (Open Graph: Slack, iMessage, LinkedIn, Facebook) | `social/link-preview-1200x630.png` | 1200 × 630 |
| X header | `social/x-header-1500x500.png` | 1500 × 500 |
| LinkedIn page banner | `social/linkedin-banner-1584x396.png` | 1584 × 396 |
| Email signature logo (show at 40 px tall) | `email/signature-lockup-80.png` | 2× |
| Email signature picture (show at 96 px) | `email/signature-avatar-192.png` | 2× |
| Browser tab | `favicon/favicon.ico` (16, 32, 48) and `favicon/favicon.svg` | |
| iPhone home screen | `favicon/apple-touch-icon.png` | 180 × 180 |
| Android, web app manifest | `favicon/android-chrome-192.png`, `-512.png` | |
| Logo on a light page, slide or document | `logo/statera-lockup-ink.svg` (or `-64/-128/-256.png`) | |
| Logo on a dark background | `logo/statera-lockup-cream.svg` | |
| Mark alone, where the name is already present | `logo/statera-mark-ink.svg`, `-cream`, `-terracotta` | 512 to 2048 px PNGs |
| Arca, the product | `logo/arca-mark.svg`, `logo/arca-mark-on-terracotta.svg` | 256 to 1024 px PNGs |

The avatars come in `terracotta` (default), `paper` and `ink`. All are
square and full bleed, with the mark centred so a circle crop keeps it whole.
The X and LinkedIn banners keep their words on the right, because both sites
put the profile picture over the bottom left.

## Per platform

`platforms/` has each site's files already at its recommended size, named for
where they go. Upload them as they are. Banners come as PNG and JPG.

| Platform | Files |
| --- | --- |
| Google Workspace | `profile-photo-800.png` (account and Chat photo); `admin-console-logo-320x132.png` (Admin console → Account → Personalization) |
| GitHub | `org-avatar-500.png`; `social-preview-1280x640` (repo Settings → Social preview) |
| LinkedIn | `company-logo-400.png`; `company-cover-1128x191`; `personal-banner-1584x396`; `shared-link-1200x627` |
| X | `profile-400.png`; `header-1500x500` |
| Facebook | `profile-720.png`; `cover-1640x624` (2× of the 820×312 desktop cover; words kept central for phones) |
| Instagram, Threads | `profile-1080.png` |
| YouTube | `channel-picture-800.png`; `banner-2560x1440` (words inside the 1546×423 area every device shows); `watermark-150.png` |
| Slack | `workspace-icon-1024.png` |
| Discord | `server-icon-1024.png`; `server-banner-960x540` |
| Microsoft Teams | `team-picture-1024.png` |
| Zoom | `profile-1024.png` |
| Bluesky | `avatar-1000.png`; `banner-3000x1000` |
| Mastodon | `avatar-400.png`; `header-1500x500` |
| Gravatar | `avatar-2048.png` |

Every profile picture is the terracotta avatar; they are all square and safe
inside a circle crop. Sizes are each platform's published recommendation as of
late 2026, rounded up where a site scales images down. If a site rejects a
file, check its current size limit and use the nearest size in `avatar/`.

## Use

- Prefer SVG wherever it is accepted, PNG otherwise, JPG only where
  transparency is refused.
- Leave clear space around the mark or lockup of at least the hook's diameter.
- Don't recolour outside the four colours above, stretch, rotate, or set the
  wordmark in another face. The lockup's wordmark is outlined, so it needs no
  font installed.
