# Vegas Munchies Map

GitHub Pages site, built with GitHub's Jekyll and a custom mobile-first layout.

Licensed Las Vegas dispensaries paired with late-night eats, checked against official sources. The live site is [https://floater12.github.io/vegas-munchies-map/](https://floater12.github.io/vegas-munchies-map/).

The home page and four area pages are published. Do not change prices, hours, addresses, license numbers, sources, or dates unless a new official check replaces them.

## Add an area page

1. Copy `_drafts/page-template.md` to a new Markdown file in the repository root.
2. Add a relative link to that file in the **Pages** list on `index.md`.
3. Add the filename to `header_pages` in `_config.yml`.

`_drafts/` is not published. Jekyll turns a relative `page.md` link into the built page URL under `/vegas-munchies-map`.
