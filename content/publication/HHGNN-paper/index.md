---
title: "Heterogeneous hypergraph neural network for friend recommendation with human mobility"
authors:
- admin
- Zipei Fan, Jixiao Zhang, Dengheng Shi, Tianqi Xu, Du Yin, Jinliang Deng, Xuan Song

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: "2022-10-17T00:00:00Z"
doi: "10.1145/3511808.3557609"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-17T00:00:00Z"

track: Short paper

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 31st ACM International Conference on Information & Knowledge Management"
publication_short: "**CIKM'22**"

abstract: Friend recommendation from human mobility is a vital real-world application of location-based social networks (LBSN). It is necessary to recognize patterns from human mobility to assist friend recommendation because previous works have shown complex relations between them. However, most of previous works either modelled social networks and user trajectories separately, or only used classical simple graph-based methods with an edge linking two nodes that cannot fully model the complex data structure of LBSN. Inspired by the fact that hyperedges can connect multiple nodes of different types, we model user trajectories and check-in records as hyperedges in a novel heterogeneous LBSN hypergraph to represent complex spatio-temporal information. And then, we design a type-specific attention mechanism for an end-to-end trainable heterogeneous hypergraph neural network (HHGNN) with supervised contrastive learning, which can learn hypergraph node embedding for the next friend recommendation task. At last, our model HHGNN outperforms the state-of-the-art methods on four real-world city datasets, while ablation studies also confirm the effectiveness of each model part.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://dl.acm.org/doi/abs/10.1145/3511808.3557609
url_code: 'https://github.com/liyongkang123/HHGNN'
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
