# Failed renders never raise

```console
pip install mkquartodocs==0.7.0 mkdocs==1.6.1 jupyter
mkdocs build; echo "exit=$?"
```

Quarto fails 5 times, but the build exits with status 0.
