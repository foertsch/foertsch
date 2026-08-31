## Arion Foertsch

Bioinformatician based in Zurich. I build analysis pipelines, data tools, and scientific software — with a research background in functional genomics, chromatin biology, and multi-omics that keeps the biology honest.

Currently at the Functional Genomics Center Zurich (FGCZ).

---

### Software & Tools

**[bulk_rna_explorer](https://github.com/foertsch/bulk_rna_explorer)** — Interactive Shiny app for exploring bulk RNA-seq DESeq2/edgeR results. Dynamic column mapping for any `SummarizedExperiment`, volcano and PCA plots, click-to-plot expression barplots, PNG/PDF export. testthat suite, GitHub Actions CI on Ubuntu + Windows.

[![CI](https://img.shields.io/github/actions/workflow/status/foertsch/bulk_rna_explorer/ci.yml?branch=main&label=CI&style=flat-square)](https://github.com/foertsch/bulk_rna_explorer/actions/workflows/ci.yml)

**[mismap-qc](https://github.com/foertsch/mismap-qc)** — Python package for visualising missing-data patterns in RNA-Seq and proteomics QC. Hierarchical clustering, multi-level annotations, interactive Plotly export. Published on [PyPI](https://pypi.org/project/mismap-qc/), conda-forge submission in review. pytest suite, GitHub Actions CI across Python 3.10–3.13 on Linux and macOS.

[![PyPI](https://img.shields.io/pypi/v/mismap-qc?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/mismap-qc/)
[![Tests](https://img.shields.io/github/actions/workflow/status/foertsch/mismap-qc/tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/foertsch/mismap-qc/actions/workflows/tests.yml)
[![Python](https://img.shields.io/pypi/pyversions/mismap-qc?style=flat-square)](https://pypi.org/project/mismap-qc/)

**[Task Tracker](https://github.com/foertsch/Task_Tracker)** — Full-stack productivity app in Flask + HTMX with CSV-backed persistence, workout tracking, Bring! API integration, and a macOS app bundle. 77 passing tests, GitHub Actions CI.

[![Tests](https://img.shields.io/github/actions/workflow/status/foertsch/Task_Tracker/test.yml?branch=main&label=tests&style=flat-square)](https://github.com/foertsch/Task_Tracker/actions/workflows/test.yml)

**[nd2_export](https://github.com/foertsch/nd2_export)** — Streaming ND2 → OME-TIFF exporter for microscopy files too large for Fiji/ImageJ. Lazy reading, incremental writing, CLI + GUI, Windows `.exe` build via PyInstaller.

---

### Research Analysis

**[MSLc_Gene_Priming_public](https://github.com/foertsch/MSLc_Gene_Priming_public)** — Reproducible analysis for [Foertsch et al., *Science Advances* (2025)](https://www.science.org/doi/10.1126/sciadv.adz8889) — MSLc-mediated epigenetic priming of neurodevelopmental genes during early neurogenesis. Single-cell multiomics, enhancer-promoter contacts, directed differentiation models. Data deposited at GEO (GSE298000–GSE298010) and Zenodo.

[![Science Advances](https://img.shields.io/badge/Science%20Advances-10.1126%2Fsciadv.adz8889-990000?style=flat-square)](https://doi.org/10.1126/sciadv.adz8889)
[![Zenodo](https://img.shields.io/badge/Zenodo-10.5281%2Fzenodo.15471244-1682D4?style=flat-square)](https://doi.org/10.5281/zenodo.15471244)

---

### Side Projects

**[bruenneli](https://github.com/foertsch/bruenneli)** — Finds the nearest public drinking fountain in Switzerland and gives walking directions to it. Next.js/TypeScript, build-time data pipeline covering Basel, Zürich, and OpenStreetMap (~15,000 fountains), fully offline-capable PWA, no runtime API. Deliberate design sibling of [scooterino](https://github.com/foertsch/scooterino).

**[scooterino](https://github.com/foertsch/scooterino)** — Finds the nearest *reachable* shared scooter/bike in Basel, Zürich, and the Glattal, ranked by real OSRM walking time (not straight-line) across 9 aggregated GBFS operator feeds. Flask + vanilla JS/CSS, no paid APIs, a weekly GitHub Action that discovers new operator feeds automatically, 67-test pytest suite, GitHub Actions CI. Deliberate design sibling of [bruenneli](https://github.com/foertsch/bruenneli).

[![Tests](https://img.shields.io/github/actions/workflow/status/foertsch/scooterino/tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/foertsch/scooterino/actions/workflows/tests.yml)

---

### Stack

**Languages**: R, Python, Bash

**Software engineering**: Python packaging (PyPI / conda-forge), pytest, GitHub Actions CI, Flask, HTMX, CLI tools

**Bioinformatics**: Seurat, DESeq2, edgeR, Signac, MOFA2, clusterProfiler, SnakePipes, deepTools, SAMtools, BEDTools

**Data & ML**: Pandas, NumPy, SciPy, scikit-learn, XGBoost, SHAP

**Visualization**: ggplot2, matplotlib, Plotly

---

<!-- NOTE: served from a third-party github-readme-stats deployment, not one I control.
     The official instance (github-readme-stats.vercel.app) is rate-limit exhausted and 503s.
     To self-host: fork anuraghazra/github-readme-stats, deploy to Vercel, set PAT_1, swap the host below. -->
[![GitHub stats](https://github-readme-stats-eight-theta.vercel.app/api?username=foertsch&show_icons=true&theme=calm&include_all_commits=true&count_private=true)](https://github.com/foertsch)
