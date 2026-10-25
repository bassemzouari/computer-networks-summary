# Computer Networks and Distributed Systems — Notes

LaTeX notes in German for *Computernetze und verteilte Systeme* (summer semester 2025).

I collected explanations and examples on network architecture, addressing, routing, and the protocols used to connect networks. The notes include topics such as distance-vector and link-state routing, autonomous systems, and IP networking.

[Read the PDF](output/summary.pdf)

## Current scope

`main.tex` includes chapters 1–4. A fifth chapter file exists, but it currently contains only a heading for multicast and is **not** part of the compiled document. This is a partial course summary.

## Files

- [Compiled PDF](output/summary.pdf)
- `main.tex`: document entry point
- `chapters/`: LaTeX source for individual topics
- `styles/`: local document class and style files

## Notes on building and reuse

The sources use a customized TU Darmstadt LaTeX template (see `styles/`) and require a suitable TeX setup. Packages used by the template may require shell escape and Pygments. The PDF above is provided for reading without a local build.

These are personal study notes, not official teaching materials. The repository's [MIT license](LICENSE) does not override the rights or licenses of third-party figures, course materials, or template components.
