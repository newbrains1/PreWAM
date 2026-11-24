# PreWAM project page

Static academic project website. Plain HTML, CSS and JavaScript; no build step.

## Local preview

```sh
python -m http.server 8765
```

Open http://localhost:8765/ in a browser.

## GitHub Pages

Repository: `newbrains1/PreWAM`. In Settings → Pages, select Deploy from a branch, then `main` and `/ (root)`.

Project URL: https://newbrains1.github.io/PreWAM/

`assets/papers/PreWAM.pdf` is the current paper draft. Add the arXiv link and identifier after it is assigned. Research-code links should be added when code is released.

## Materials

The sole real-world video is the complete, 1×-speed horizontal demonstration provided by the authors, encoded to 1920×720 for web delivery. Scientific figures and reported numbers come from the PreWAM manuscript. The abstract is reproduced verbatim.

The layout is original. The JEPA-WAM and VLA-JEPA project pages informed the content organization; their code and assets are not redistributed.

## Page structure

Abstract → real-world video → controlled prediction-space study → method → benchmark comparisons → ablations and perturbation analysis → citation.

The seven HTML tables reproduce the six manuscript tables, with SimplerEnv split by embodiment. Reported values, bold entries, and recomputed-mean markers are retained.
