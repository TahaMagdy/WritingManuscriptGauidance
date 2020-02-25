# Writing Manuscript Gauidance

- `main.tex` is a tex file that orchestrates the manuscript body.
- Every section should be in a standalone tex file.
- All literature papers should be grouped in a directory called `Publications`, accompanied with their `bib` file. 



## Organizing Literature Lapers inside `Publications`
- Papers files names should follow that pattern `FirstAuthorName_Year_PaperTitle.pdf` **Without including the underscores**.
- The Paper file name (pdf name) should be used as the paper key entry in `bib` files.
- Keep the publications `bib` file updated with the `Publication` content.


## Compilation 
`$ latexmk -xelatex main`
