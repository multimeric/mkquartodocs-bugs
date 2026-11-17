# `format:` is ignored

```console
git clone -b format-ignored https://github.com/multimeric/mkquartodocs-bugs.git
cd mkquartodocs-bugs
pip install mkquartodocs==0.7.0 mkdocs==1.6.1 jupyter
mkdocs build
cat docs/index.md
```

`docs/index.md` is Pandoc Markdown, not GFM.
