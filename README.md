# biogram

Extraction and analysis of n-grams (k-mers) from biological sequences, with a quick permutation test (QuiPT) for feature filtering.

Compatibility updates by Renova.

Version 1.6.3.9001 changes only documentation: links to the optional `seqinr` package that did not resolve are written as plain text, three unbraced `{b}` are written as `\code{b}`, and the `\value` list in the `cluster_reg_exp` help page uses valid `\item` markup. No R function was changed.

## Install

```r
install.packages("biogram", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/biogram@renova-1.6.3.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

biogram is by Michal Burdukiewicz (maintainer), Piotr Sobczyk, Chris Lauber and Dominik Rafacz, with a contribution from Katarzyna Sidorczuk; the original project is at <https://github.com/michbur/biogram>. See `citation("biogram")`. License: GPL-3; see [COPYING](COPYING).
