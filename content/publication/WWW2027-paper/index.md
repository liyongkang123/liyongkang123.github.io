---
title: "Relevance-Guided Residual Calibration for Spectral Compression of Dense Retrieval Embeddings"
authors:
- admin
- Panagiotis Eustratiadis, Evangelos Kanoulas
date: "2026-10-26T00:00:00Z"
doi: "10.48550/arXiv.2610.37707"
 
# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-26T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2610.37707 (Under Review)"
publication_short: "**Preprint (Under Review)**"

abstract: "Spectral compression reduces the storage and scoring costs of dense retrieval by projecting embeddings onto a smaller principal subspace. However, its corpus-derived weighting rules tie all retained directions to a shared spectral trend, without directly accounting for their individual contributions to relevance. To address this, we propose Relevance-Guided Residual Calibration (RRC), a closed-form method for refining spectral weights using relevance judgments. RRC estimates margin-based weights from the means and variances of positive--negative score contributions along each retained direction. It retains directions with positive estimated weights, decomposes their log weights into a fitted power-law trend and a residual, and adds the residual to the compressor's log weights on this support. This allows relevance judgments to adjust individual directions while preserving the compressor's overall spectral trend. RRC applies to PCA, Whitening, and SpecTemp, and incorporates the corrections into the existing transformation shared by documents and queries, without iterative model training or an additional inference stage. Experiments with three encoders on nine datasets covering conventional and reasoning-intensive retrieval show that SpecTemp + RRC achieves the highest mean effectiveness among tested compressors on the BEIR group and BRIGHT at every target dimension. On the five evaluated BRIGHT datasets, it improves over SpecTemp by an average of 2.34 nDCG@10 points at 768 dimensions. The gains also persist under scalar and product quantization, improving the trade-off between per-document storage and retrieval effectiveness. Our code is available at: this https URL."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: 'https://arxiv.org/abs/2610.37707'
url_code: 'https://anonymous.4open.science/r/rrc-spectral-compression-B5CE/'
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
