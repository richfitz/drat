# richfitz/drat

Our [drat](https://github.com/eddelbuettel/drat) repository.  Plaese see [the webpage](https://outbreakresources.github.io/drat) for more information.

# Updating the website

To rebuild the repository install `drat.builder` with

```
drat:::add("richfitz")
install.packages("drat.builder")
```

Rebuild the repository with:
```
drat.builder::build()
```

Or from the command line with

```
./drat.builder
```

After rebuilding, push with:

```
git push
```

If you removed history (with the `drop_history` argument or `--drop-history` switch) then you'll need to add a `-f` to that push.
