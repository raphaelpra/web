---
celltoolbar: Slideshow
jupytext:
  cell_metadata_filter: all,-hidden,-heading_collapsed,-run_control,-trusted
  formats: md:myst
  notebook_metadata_filter: all,-language_info,-toc,-jupytext.text_representation.jupytext_version,-jupytext.text_representation.format_version
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: JavaScript (Node.js)
  language: javascript
  name: javascript
language_info:
  name: javascript
nbhosting:
  title: 'practice : games'
---

+++

Licence CC BY-NC-ND, Thierry Parmentelat

+++

# practice : games

```{code-cell}
tools = require('../js/tools'); tools.init()
```

## tic-tac-toe

+++

write a tic-tac-toe game, something like this - there is a lot of room for improvement !

```{code-cell}
:tags: [hide-input]

tools.sample_from_stem("../samples/45-tic-tac-toe/tic-tac-toe",
                       {sources_show: false, separate_height: '400px', separate_width: '400px'})
```

## minesweeper

+++

write a minesweeper game; again you can do better than this :)

```{code-cell}
:tags: [hide-input]

tools.sample_from_stem("../samples/45-minesweeper/minesweeper",
                       {sources_show: false, separate_height: '400px', separate_width: '400px'})
```
