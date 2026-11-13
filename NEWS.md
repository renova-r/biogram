# biogram 1.6.3.9001

Renova release, based on CRAN biogram 1.6.3 (archived on CRAN 2026-11-03).

- `R/read_fasta.R`, `R/seq2matrix.R`, `man/read_fasta.Rd`, `man/write_fasta.Rd` and `man/list2matrix.Rd`: `\link[seqinr]{read.fasta}` and `\link[seqinr]{write.fasta}` became plain text naming the functions from the `seqinr` package (not a dependency).
- `man/calc_ed.Rd`, `man/calc_pi.Rd`, `man/calc_si.Rd`: `{b}` became `\code{b}`.
- `man/cluster_reg_exp.Rd`: the `\itemize{ \item{...}{...} }` block in `\value` became plain `\item{name}{description}` entries.
- Documentation only: no R function body, `NAMESPACE` or `DESCRIPTION` change.
- `DESCRIPTION`: `Version` set to `1.6.3.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL text) was added; the `License` field is unchanged.
- `README.md` was replaced by a short Renova README and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.
