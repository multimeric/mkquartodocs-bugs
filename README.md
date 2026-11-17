# Existing `.md` files are overwritten

```console
git clone -b overwrites-existing-md https://github.com/multimeric/mkquartodocs-bugs.git
cd mkquartodocs-bugs
touch docs/index.qmd
uv run mkdocs build
cat docs/index.md
```

`docs/index.md` is replaced by Quarto's output and not restored.
