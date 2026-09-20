# Reinforcement Learning lecture

## Compile the slides

Requirements: a LaTeX distribution with `latexmk`, Beamer, the Metropolis theme,
and the packages used by the source file (`tikz-qtree`, `txfonts`, and `natbib`).

From the project root, run:

```sh
cd slides
latexmk -pdf -interaction=nonstopmode l7-MLandLM25-RL.tex
```

The compiled PDF is written to `slides/l7-MLandLM25-RL.pdf`.

To remove generated LaTeX compilation files, run this from `slides/`:

```sh
latexmk -c l7-MLandLM25-RL.tex
```

The source is [slides/l7-MLandLM25-RL.tex](slides/l7-MLandLM25-RL.tex); figures
are stored in [figures/](figures/).
