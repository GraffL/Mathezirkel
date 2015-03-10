## Dependencies

Install [diagrams-rubiks-cube][diagrams-rubiks-cube]:

```bash
$ cabal update
$ cabal install diagrams-rubiks-cube
```

Install `diagrams-builder` with Cairo backend:

```bash
$ cabal install -fcairo diagrams-builder
```

## Compilation

To compile, call LaTeX with

```bash
$ pdflatex --enable-write18 anleitung.tex
```

diagrams-rubiks-cube: https://github.com/timjb/diagrams-rubiks-cube