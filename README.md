# GESIS Surf: An Open-Source Infrastructure for Privacy-Preserving Longitudinal Web Browsing Data Collection

LaTeX source of the paper describing [GESIS Surf](https://github.com/gesiscss/gesis_surf_extension),
a browser extension and backend for collecting web browsing data in academic panel studies.

**Authors:** Mario Alberto Ramirez, Frank Mangold, Sebastian Stier
(GESIS – Leibniz Institute for the Social Sciences; University of Mannheim)

**Status:** submitted to *SoftwareX* (October 2026).
**Preprint:** arXiv link will be added once the preprint is announced.

The software itself is in a separate repository:
<https://github.com/gesiscss/gesis_surf_extension>.

## Contents

```
arxiv/
├── main.tex        # paper source (arXiv preprint version)
├── main.bib        # references
├── latexmkrc       # build settings for latexmk
└── figures/        # architecture diagrams
```

## Building the PDF

Choose one of three ways.

### 1. Locally with VS Code and TeX Live

Requires a TeX Live installation (2023 or newer) and VS Code.

1. Open this folder in VS Code and install the recommended extension
   *LaTeX Workshop* when prompted.
2. Open `arxiv/main.tex` and save it. The PDF builds automatically and opens in a tab.

From a terminal instead:

```bash
cd arxiv
latexmk main.tex
```

### 2. In a Dev Container (no TeX installation needed)

Requires Docker and VS Code with the *Dev Containers* extension.

1. Open this folder in VS Code.
2. Choose **Reopen in Container** when prompted
   (or run *Dev Containers: Reopen in Container* from the command palette).
   The first start downloads the TeX Live 2025 image (about 2.6 GB).
3. Open `arxiv/main.tex` and save it to build the PDF.

### 3. On Overleaf (browser only)

1. Zip the **contents** of the `arxiv/` folder (`main.tex`, `main.bib`, `latexmkrc`, `figures/`).
2. In Overleaf, choose **New Project → Upload Project** and select the zip file.

## Citation

Until the article is published, please cite the preprint. Citation metadata is in
[`CITATION.cff`](CITATION.cff); GitHub shows it under **Cite this repository**.

## License

The paper text and figures are licensed under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) (see [`LICENSE`](LICENSE)).
The GESIS Surf software is licensed separately under the MIT License in its own repository.
