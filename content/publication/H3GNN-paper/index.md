---
title: "Heterogeneous Hyperbolic Hypergraph Neural Network for Friend Recommendation in Location-based Social Networks"
authors:
- admin
- Zipei Fan, Xuan Song

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: "2024-12-05T00:00:00Z"
doi: "10.1145/3708999" 

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-05T00:00:00Z"

track: Journal paper

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Knowledge Discovery from Data"
publication_short: "**TKDD2024**"

abstract: Friend recommendation is an important real-world application in location-based social networks (LBSN), helping users discover potential friends and enhance their overall happiness. LBSN mainly comprises two distinct data structures, spatio-temporal data for human mobility and graph data for social networks. These two data structures make it challenging to model the complex relationships between them, which are essential for comprehensively understanding users’ lives. Previous studies have either modeled user trajectories and social networks separately or used classical simple graph-based methods, where a simple edge links only two nodes, failing to capture the multiple relationships inherent in LBSN. Furthermore, most studies have relied on Euclidean space to train their graph models, which could result in significant distortion because of tree-like social network data structure. To address these limitations, we propose a novel heterogeneous LBSN hypergraph that represents user check-in records and continuous trajectories—comprising multiple Points of Interest (POI)—as hyperedges, enabling the representation of complex spatio-temporal relationships. This approach enables us to link multiple nodes of different types by hyperedges and use hyperbolic spaces to create more efficient graph representations. Additionally, we devise a new type-specific attention mechanism for our Heterogeneous Hyperbolic Hypergraph Neural Network (H3GNN), which is end-to-end trainable and employs supervised contrastive learning to learn hypergraph node embeddings for the subsequent friend recommendation task with the help of hyperbolic space. Finally, our model H3GNN achieves better results than existing methods on six real-world city datasets, and our ablation studies demonstrate the effectiveness of each component. Additionally, our experiments indicate that H3GNN requires less data storage and training time compared to previous methods.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://dl.acm.org/doi/10.1145/3708999
url_code: 'https://github.com/liyongkang123/H3GNN'
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
