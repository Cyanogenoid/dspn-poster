# dspn-poster

This repo contains the LaTeX poster style I used for my [poster on Deep Set Prediction Networks](https://www.cyanogenoid.com/files/dspn-poster.pdf).
It uses the tikzposter package and has a University of Southampton theme.
The main bits are in `template.tex` and `poster.tex`.
`poster.tex` is the main file you would edit if you want to use this repo as a starting point for your own poster.
To create the pdf, run `make`, which calls `latexmk -pdf poster.tex`.
If you want to use this poster as a template, you probably want to remove all the files in the `resources` directory and the `tikz.tex` file.
