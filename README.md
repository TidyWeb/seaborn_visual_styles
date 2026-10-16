# Seaborn Visual Styles

## [🌐 Open the live site: https://tidyweb.github.io/seaborn_visual_styles/ ↗](https://tidyweb.github.io/seaborn_visual_styles/)


This is a representative visual atlas of the official [Seaborn example gallery](https://seaborn.pydata.org/examples/index.html). It gives each captured example a permanently visible title, the Seaborn function that calls it, a representative code call, and a short explanation of the switches that can change the display.

The guide is deliberately more than a contact sheet. Its opening data-vocabulary section explains the difference between measurements, categories, ordered categories, time, and identifiers before the gallery is organised into relationships, distributions, categorical comparisons, regression, matrices, grids and composition, and Seaborn objects. Each family also has a switch map: a quick reminder that the method supplies the general display while keyword arguments control its visual semantics.

## What is included

- **49 official gallery examples**, represented by **22 distinct Seaborn function labels**. This is a teaching selection, not a complete catalogue of every chart, parameter, or API feature.
- A self-contained [HTML atlas](<Seaborn Visual Styles.html>) with the visual layout, locally captured thumbnail assets, source links, and readable code blocks.
- A [Markdown companion](<Seaborn Visual Styles.md>) for text-first reading, searching, and reuse.
- The [capture manifest](assets/dataviz-seaborn-visual-styles-20260820/manifest.json), which records each example's official source page, image source, title, family, call, and local asset path.

The labels and thumbnails come from Seaborn's public documentation. The official examples and assets remain subject to the Seaborn project's own documentation and distribution terms; check upstream terms before redistributing them outside this study/reference presentation.

## View the atlas locally

From the repository root, start a small local web server:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/Seaborn%20Visual%20Styles.html> in a browser. Opening the HTML file directly will also work in most browsers, but a local server preserves the cleanest behaviour for relative links and assets.

## Why there is no PDF

The PDF is a personal print/reference version and is intentionally not part of this public repository. The HTML is the primary, inspectable artifact; the Markdown file provides a lightweight companion.

## Upstream references

- [Seaborn example gallery](https://seaborn.pydata.org/examples/index.html)
- [Seaborn function overview](https://seaborn.pydata.org/api.html)
- [Seaborn objects interface](https://seaborn.pydata.org/tutorial/objects_interface.html)
