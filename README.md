# Erdős Distance Lab

Standalone interactive geometry sandbox for [AI-Talks.org](https://ai-talks.org), based on the Erdős unit-distance problem.

**Public website (GitHub Pages):** https://mvbp-ai-talks-org.github.io/erdos-distance-lab/

## Features

- Drag and add points to a 2D configuration and count nearly unit-distance pairs.
- Compare square, triangular, rescaled square lattices (including knight-move connections), polygons, and random point configurations.
- Adjust the number of points and highlighting tolerance, explore heuristic local adjustments, and save PNG screenshots.
- Responsive, self-contained HTML5 Canvas app: no installation, build step, libraries, or server required.

## GitHub Pages setup

In this repository select **Settings → Pages → Build and deployment → Deploy from a branch**, then choose **main** and **/(root)** and click **Save**. The `index.html` in the repository root becomes the homepage.

This repository is separate from `murmuration-lab`; no files in the Murmuration Lab need to be changed.

## Mathematical note

The browser counts distances within an adjustable numerical tolerance, whereas Erdős's mathematical problem concerns points **exactly** one unit apart. Its demonstrations concern finite arrangements and are not a reproduction or a verification of the 2026 asymptotic counterexample.

Reference: [Alon et al. (2026)](https://arxiv.org/abs/2605.20695).
