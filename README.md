# replace_pweave
Use `Rmarkdown` and the `reticulate` package to replace `Pweave`

In 2012 [John Cook](https://www.johndcook.com/blog/2012/12/20/basics-of-sweave-and-pweave/)
explained how to make reproducible reports in Python using `Pweave` to process
the code chunks. The entire document is composed in LaTeX.

`Rmarkdown` in RStudio integrates an environment where most text is written in
`markdown`.  \LaTeX is supported and is used mostly for mathematics. One can
also use the same document to generate documents in PDF, HTML, and Word formats.
The conversion is handled by `pandoc`. The `.Rmd` file implements John Cook's
exemplar in Rmarkdown. Using Rstudio (with pandoc) the document can be processed
to PDF or HTML format.
