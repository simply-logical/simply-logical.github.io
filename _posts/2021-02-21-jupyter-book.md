---
layout: post
title: SWISH extension for Jupyter Book
tags: [general, book]
---

We have just released a brand new extension for [Jupyter Book] that allows to *auto-magically* insert interactive SWI Prolog code boxes via SWISH using a simple ([MyST]) Markdown syntax.

The extension source code is hosted on GitHub, in the [simply-logical/sphinx-prolog] repository.
To insert a simple interactive code box, it's enough to list the Prolog code within the *swish* directive:
````Markdown
```{swish} swish:box-id
prolog :- code.
```
````

To help you get started with your executable [Jupyter Book] infused with interactive SWISH Prolog code boxes, we published a simple template on GitHub.
It is available in the [simply-logical/prolog-book-template] repository.
This template is rendered and hosted on GitHub Pages at <https://book-template.simply-logical.space/>, which page also serves as a user guide to the [sphinx-prolog] Jupyter Book extension.

Enjoy creating your interactive Prolog materials!

[Jupyter Book]: https://jupyterbook.org/
[MyST]: https://myst-parser.readthedocs.io/
[simply-logical/sphinx-prolog]: https://github.com/simply-logical/sphinx-prolog
[sphinx-prolog]: https://github.com/simply-logical/sphinx-prolog
[simply-logical/prolog-book-template]: https://github.com/simply-logical/prolog-book-template
