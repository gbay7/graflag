# GraFlag — JMLR paper

Source for the JMLR (MLOSS) paper describing GraFlag.

**Title:** *GraFlag: Reproducible Distributed Benchmarking for Graph Anomaly Detection*

## Build

Requires a TeX Live installation with `latexmk`, `pdflatex`, and `bibtex`.

```bash
latexmk -pdf graflag-jmlr.tex
```

The current build (`graflag-jmlr.pdf`) is committed for convenience.

## Files

- `graflag-jmlr.tex` — paper source
- `graflag.bib` — bibliography
- `arch.tex` — TikZ architecture figure included via `\input{arch}`
- `dashboard.png` — web dashboard screenshot
- `jmlr/jmlr2e.sty` — JMLR paper style
- `graflag-jmlr.pdf` — latest rendered PDF
