# Files mkdocs ignores are rendered

```console
git clone -b renders-ignored-files https://github.com/multimeric/mkquartodocs-bugs.git
cd mkquartodocs-bugs
uv run mkdocs build
```

`.hidden/hidden.qmd` and `site/stale.qmd` are rendered, although mkdocs ignores both.
