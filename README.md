# Project Page — Federated Vector Retrieval across Heterogeneous VectorDBs

Static project website for our paper introducing **HVMap**, a lightweight compatibility layer for
federated retrieval across vectorDBs built with different embedding models.

## Contents

```
index.html        # the page
static/css/        static/js/        static/images/   # assets (figures as SVG)
server.py         # optional local preview server
```

## Preview locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000/index.html
```

> Equations are rendered with [MathJax](https://www.mathjax.org/) (loaded from CDN, so a network
> connection is needed for math to display). The site is adapted from the
> [Nerfies](https://github.com/nerfies/nerfies.github.io) template (CC BY-SA 4.0).
