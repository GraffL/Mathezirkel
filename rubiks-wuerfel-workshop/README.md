## Dependencies

Install [rubiks-cube][rubiks-cube]:

```bash
$ git clone https://github.com/timjb/rubiks-cube.git
$ cd rubiks-cube
$ cabal install
```

Install `diagrams-builder` with Cairo backend:

```bash
$ cabal update
$ cabal install -fcairo diagrams-builder
```

## Compilation

To compile, call LaTeX with

```bash
$ pdflatex --enable-write18 anleitung.tex
```

rubiks-cube: https://github.com/timjb/rubiks-cube