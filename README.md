# Toronto: Streetwear & Art

Single-page tip sheet for PJ and Jillian's drive up through Niagara into
Toronto. Shops and galleries picked for two working artists — craft and
curation over "trendy."

## Structure

```
index.html      the whole page, self-contained, no build step
```

Sticky filter bar (All / Streetwear / Sneakers / Galleries / Vintage) toggles
cards by category with vanilla JS. Each place is a flip card — tap it for
address, a "why they'd like it" note, and a Google Maps link (search results
include reviews, no embedded map needed).

## Run it

Just open `index.html`. No server needed, no dependencies beyond a Google
Fonts CDN link.

## Deploy

GitHub Pages, no build step. Settings > Pages > deploy from branch, root of
`main`. `.nojekyll` is in place in case that ever matters.
