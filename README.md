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

Paper links point to https://arxiv.org/abs/2611.31901. Research-code links should be added when code is released.

## Materials

The sole real-world video is the complete, 1×-speed horizontal demonstration provided by the authors, encoded to 1920×720 for web delivery. Scientific figures and reported numbers come from the PreWAM manuscript. The abstract is reproduced verbatim.

The layout is implemented locally. JEPA-WAM and VLA-JEPA informed the content organization; GAWM informed the November 2026 typography and hierarchy refresh. Their code and assets are not redistributed. The latest refinement uses charcoal text with restrained burnt-orange accents; scientific figures retain their original colors.

## Page structure

Abstract → real-world video → simulation rollouts → contributions → controlled prediction-space study → method → pretraining/posttraining/inference → benchmark comparisons → ablations and perturbation analysis → citation.

The seven HTML tables reproduce the six manuscript tables, with SimplerEnv split by embodiment. Reported values, bold entries, and recomputed-mean markers are retained.
