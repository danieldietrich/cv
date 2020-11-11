# Curriculum Vitae

LaTeX source for the [CV of Daniel Dietrich](https://cv.danieldietrich.dev)

Download the .pdf version [here](https://cv.danieldietrich.dev/daniel-dietrich-cv.pdf).

## Instructions

The CV is automatically deployed to [gh-pages](https://pages.github.com) by a [GitHub Action](.github/workflows/deploy.yml) when pushing to the `main` branch.

To manually build the pdf on a local machine, an installation of [Texlive](https://www.tug.org/texlive/) is required.

```sh
pdflatex daniel-dietrich-cv.tex
```

The output is written to the file `daniel-dietrich-cv.pdf`.