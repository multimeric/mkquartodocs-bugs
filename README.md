# Failed renders never raise

```console
git clone -b retry-never-raises https://github.com/multimeric/mkquartodocs-bugs.git
cd mkquartodocs-bugs
uv run mkdocs build
echo $?
```

Quarto fails 5 times, but the build exits with status 0.
