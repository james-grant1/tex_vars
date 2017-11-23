# tex_vars
Include variables within latex

Example of how to include variables within latex using pythontex based on [this](https://tex.stackexchange.com/questions/122003/is-there-a-pythontex-equivalent-to-sexpr-in-r)

Two example cases are given:

| simple
| model

simple takes a single input test.tex file with all components included.

model is a possible approach to including format and variable files to fit in with automated workflows.

To compile run

pdflatex test.tex
pythontex test.tex
pdflatex test.tex
