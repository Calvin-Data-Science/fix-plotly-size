# FixPlotlySize Extension For Quarto

Work around a bug in Quarto or RevealJS that causes plotly plots sometimes not to get updated to the correct size. This seems to happen when there's many slides and the plot is shown outside of the range of actively visible slides.

## Installing

```bash
quarto add Calvin-Data-Science/fix-plotly-size
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

## Using

```yaml
format:
  revealjs: default
revealjs-plugins:
  - fixplotlysize
```

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).

