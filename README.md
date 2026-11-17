# Existing `.md` files are overwritten

```console
git clone -b overwrites-existing-md https://github.com/multimeric/mkquartodocs-bugs.git
cd mkquartodocs-bugs
pip install mkquartodocs==0.7.0 mkdocs==1.6.1
touch docs/index.qmd
mkdocs build
cat docs/index.md
```

`docs/index.md` is replaced by Quarto's output and not restored.
