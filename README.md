# SDM–SGS

Working research materials on field filtering in the three-location Spatial Durbin Model (SDM) and its implications for the Spirtes–Glymour–Scheines (SGS) constraint-based structure-learning algorithm.

## Contents

| File | Description |
| --- | --- |
| `paper.tex` | LaTeX source for the theoretical manuscript (article). |
| `paper.pdf` | Compiled manuscript (20 pages). |
| `slides.tex` | LaTeX source for the Beamer presentation. |
| `slides.pdf` | Compiled presentation (44 slides). |
| `algebra.html` | Companion HTML treatment of SDM field-filtering algebra. |

The PDF files are included for convenient reading; the corresponding `.tex` files are editable sources. The HTML file contains its styles and rendered mathematical markup, but also references external web resources that may require a network connection.

## Building the LaTeX documents

With a LaTeX distribution providing the packages used by the sources (including Beamer and TikZ), run:

```sh
pdflatex -interaction=nonstopmode -halt-on-error paper.tex
pdflatex -interaction=nonstopmode -halt-on-error paper.tex
pdflatex -interaction=nonstopmode -halt-on-error slides.tex
pdflatex -interaction=nonstopmode -halt-on-error slides.tex
```

## Status

Working theoretical/tutorial material, November 2026. The population-level examples make specific assumptions (including fixed covariates, independent Gaussian disturbances, and exact filtering); they should not be read as a general empirical identification result.

No license is specified at this stage.
