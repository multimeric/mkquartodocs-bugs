# Files mkdocs ignores are rendered

```console
pip install mkquartodocs==0.7.0 mkdocs==1.6.1 mkdocs-same-dir
mkdocs build
```

`.venv/hidden.qmd` and `site/stale.qmd` are rendered, although mkdocs ignores both.
