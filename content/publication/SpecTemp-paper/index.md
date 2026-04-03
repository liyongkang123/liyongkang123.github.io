---
title: "Spectral Tempering for Embedding Compression in Dense Passage Retrieval"
authors:
- admin
- Panagiotis Eustratiadis, Evangelos Kanoulas

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: "2026-04-03T00:00:00Z"
doi: "" 

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-05T00:00:00Z"

track: Short paper

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "The 49th International ACM SIGIR Conference on Research and Development in Information Retrieval"
publication_short: "**SIGIR2026(Short Paper, Oral)**"

abstract: Dimensionality reduction is critical for deploying dense retrieval systems at scale, yet mainstream post-hoc methods face a fundamental trade-off: principal component analysis (PCA) preserves dominant variance but underutilizes representational capacity, while whitening enforces isotropy at the cost of amplifying noise in the heavy-tailed eigenspectrum of retrieval embeddings. Intermediate spectral scaling methods unify these extremes by reweighting dimensions with a power coefficient $\gamma$, but treat $\gamma$ as a fixed hyperparameter that requires task-specific tuning. We show that the optimal scaling strength $\gamma$ is not a global constant, it varies systematically with target dimensionality $k$ and is governed by the signal-to-noise ratio (SNR) of the retained subspace. Based on this insight, we propose Spectral Tempering (\textbf{SpecTemp}), a learning-free method that derives an adaptive $\gamma(k)$ directly from the corpus eigenspectrum using local SNR analysis and knee-point normalization, requiring no labeled data or validation-based search. Extensive experiments demonstrate that Spectral Tempering consistently achieves near-oracle performance relative to grid-searched $\gamma^*(k)$ while remaining fully learning-free and model-agnostic. 
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'https://arxiv.org/abs/2603.19339'
url_code: 'https://github.com/liyongkang123/SpecTemp'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: '#'
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://link.springer.com/article/10.1007/s10707-022-00466-1/figures/3)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
