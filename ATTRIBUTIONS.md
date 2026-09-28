# Attributions

mbwishlist.online is a single self-contained HTML file with no build step,
no bundled JavaScript libraries, and no icon library or stock image
assets. Everything visual (icons, thumbnails) is built from CSS, emoji
characters, or photos the user uploads themselves. The only third-party
asset the page uses is listed below.

## Fonts

The page loads three typefaces from Google Fonts:

- **Fraunces** — headings
- **IBM Plex Sans** — body text
- **IBM Plex Mono** — release-note version numbers and a few small labels

All three are licensed under the [SIL Open Font License 1.1](https://scripts.sil.org/OFL),
a free license that permits use, redistribution, and embedding (including
in a project like this one) without payment and without a required
attribution notice in the product itself. This file exists as a courtesy
record of what's in use, not because the license demands it.

Fonts are loaded live from `fonts.googleapis.com` / `fonts.gstatic.com`
rather than self-hosted. This is a privacy-relevant network request (it
sends the visitor's IP address to Google, the same as loading any external
resource would) and is disclosed in the app's Privacy Policy. Self-hosting
the font files instead of loading them from Google would remove that
request entirely and is a reasonable future improvement, but was not
completed in this pass — see the audit report for details.

## Everything else

- **Icons:** Unicode emoji and symbol characters only (e.g. ✎ 🗑 ↩ ⌄ ★ ↑).
  No icon font or SVG icon library.
- **Images:** No stock photography, logos, or bundled images. Product
  thumbnails come only from photos a user uploads themselves.
- **Code:** No third-party JavaScript libraries, frameworks, or CDN
  scripts. All logic is original, hand-written vanilla JavaScript in the
  page itself.
- **Retailer names** (e.g. "Amazon," "Walmart," "Target") that appear as
  small labels on items are the trademarks of their respective owners.
  They're shown only to describe a link the user chose to paste — see the
  app's FAQ and Terms of Use for the no-affiliation disclaimer.
