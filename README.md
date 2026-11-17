# `format:` is ignored

```console
git clone -b format-ignored https://github.com/multimeric/mkquartodocs-bugs.git
cd mkquartodocs-bugs
uv run mkdocs build
cat docs/index.md
```

`docs/index.md` is Pandoc Markdown, not GFM.
