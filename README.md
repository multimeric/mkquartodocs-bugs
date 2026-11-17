# Existing `.md` files are overwritten

```console
pip install mkquartodocs==0.7.0 mkdocs==1.6.1
touch docs/index.qmd
mkdocs build
cat docs/index.md
```

`docs/index.md` is replaced by Quarto's output and not restored.
