# Anchorstone Holdings Ltd — Website

Single-page marketing site for Anchorstone Holdings Ltd, a Tanzanian business
solutions and industrial supply company serving the mining, energy,
infrastructure, and industrial sectors.

Live at: https://anchorstone.co.tz

## Stack

Plain HTML + CSS, no build step, no framework, no dependencies. One file
(`index.html`) with embedded styles. This keeps the site fast, easy to host
anywhere, and easy for a non-developer to hand-edit later.

## Structure

```
index.html    the site
favicon.svg   browser-tab icon (the Anchor Hex mark, text-weight cut)
CNAME         custom-domain config for GitHub Pages
robots.txt    search-engine crawling rules
```

## Brand

Built from the "Modern Industrial" identity system — see the brand proposal
deck for the full specification (colour system, construction grid,
production cuts, application rules). Palette and type tokens are defined as
CSS custom properties at the top of `index.html`'s `<style>` block.

- Font: IBM Plex Sans (Google Fonts)
- Primary mark: hexagon + horizontal crossbar ("The Anchor Hex")
- Palette: Graphite `#20242B`, Steel White `#EEF0F2`, Steel Blue `#5B7C99`
  (decorative/icon use only — use Steel Blue Deep `#3E5A73` or Steel Blue
  Light `#8CA3B8` for any text-scale use, per the accessibility notes in the
  brand proposal)

## Editing

Open `index.html` in any editor. Section content, copy, and contact details
are plain text in the markup — no build tooling required. Preview locally
with any static server, e.g.:

```
npx serve .
```

## Deployment

Hosted on GitHub Pages with a custom domain. To deploy a change: push to
`main` — Pages redeploys automatically. DNS for `anchorstone.co.tz` must
point at GitHub Pages (see the repo's GitHub Pages settings for the current
target IPs/CNAME target); `CNAME` in this repo tells Pages which domain to
serve on.

## Contact details on file

- Phone: +255 741 111 105
- Email: info@anchorstone.co.tz
- Address: 1620 Oysterbay, Dar es Salaam, Tanzania
