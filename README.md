# Lecture 7 for ML&LM@UvA, 2026

## Compile the slides

Requirements: a LaTeX distribution with `latexmk`, XeLaTeX, Beamer, the
Metropolis theme, and the packages used by the source file (`fontspec`,
`tikz-qtree`, and `natbib`). The source uses `Arial Unicode MS` for the star
glyph in the reward example.

From the project root, run:

```sh
cd slides
latexmk -xelatex -interaction=nonstopmode l7-MLandLM25-RL.tex
```

The compiled PDF is written to `slides/l7-MLandLM25-RL.pdf`.

To remove generated LaTeX compilation files, run this from `slides/`:

```sh
latexmk -c l7-MLandLM25-RL.tex
```

The source is [slides/l7-MLandLM25-RL.tex](slides/l7-MLandLM25-RL.tex); figures
are stored in [figures/](figures/).
