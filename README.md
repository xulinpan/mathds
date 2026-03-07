# Mathematics of Data Science — bookdown project

This repository contains a starter undergraduate textbook written in **R bookdown**.

## Contents

- 12 core chapters
- theorem-style environments via `preamble.tex`
- PDF/HTML build configuration
- bibliography support

## Build

In R:

```r
install.packages(c("bookdown", "knitr", "rmarkdown"))
bookdown::render_book("index.Rmd")
```

## Suggested next steps

1. Expand exercises with solutions.
2. Add chapter-end projects and case studies.
3. Add figures and datasets in `figures/` and `data/`.
4. Add a full chapter on calculus if your curriculum needs it.
