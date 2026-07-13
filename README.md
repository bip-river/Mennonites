# Mennonites

**The Rebaptizers — An exhibit about the Mennonites.**

An interactive web exhibit tracing the Anabaptist / Mennonite story: its origins in the
Radical Reformation, the migrations, the family tree of groups, and the ideas — believers'
baptism, nonresistance, *Gelassenheit* — that hold it together. It includes a hand-drawn
migration map, a faceted sort of groups, a lineage tree, a glossary, and source notes.

## Running it

The whole exhibit is a **single, self-contained `index.html`** — all CSS and JavaScript are
inline, the map is hand-drawn SVG, and it makes **no external network requests**. Just open
`index.html` in a browser, or serve the folder:

```sh
python3 -m http.server
```

## Live site

Published with GitHub Pages at:

<https://bip-river.github.io/mennonites/>

> To enable it, set **Settings → Pages → Source** to the default branch, folder `/ (root)`.

## License

Dual-licensed — see [`LICENSE.md`](LICENSE.md):

- **Code** (HTML/CSS/JS): [MIT License](LICENSE.md#software--mit-license)
- **Content** (text, essays, glossary): [CC BY 4.0](LICENSE.md#content--creative-commons-attribution-40-international-cc-by-40)
