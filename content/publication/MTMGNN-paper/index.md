---
title: "MTMGNN: Multi-time multi-graph neural network for metro passenger flow prediction"
authors:
- Du Yin, Renhe Jiang, Jiewen Deng
- admin
- Yi Xie, Zhongyi Wang, Yifan Zhou, Xuan Song, Jedi S Shang
date: "2022-04-01T00:00:00Z"
doi: "10.1007/s10707-022-00466-1"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "GeoInformatica Journal"

abstract: The passenger flow prediction of the public metro system is a core and critical part of the intelligent transportation system, and is essential for traffic management, metro planning, and emergency safety measures. Most methods chose the recent segment from historical data as input to predict the future traffic flow; however, this would lead to the loss of the inherent characteristic information of the metro passenger flow’s daily morning and evening peak. Therefore, this study aggregates the recent-term and long-term information and use a long-term Gated Convolutional Neural Network (Gated CNN) to extract the temporal feature from the complex historical data. On the other hand, typical models did not consider the different spatial dependencies between different metro stations; this work proposes various adjacent relationships to characterize the degree of association between nodes. In order to extract spatial and temporal features at the same time, the historical data of recent-term and long-term is merged together to extract spatial features through a multi-graph neural network module. By combining Gated CNN and multi-graph module, we propose a multi-time multi-graph neural network named MTMGNN for metro passenger flow prediction. The result of our experiment on real-world datasets shows that our model MTMGNN is better than all state-of-art methods.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://link.springer.com/article/10.1007/s10707-022-00466-1
url_code: 'https://github.com/lixus7/MTMGNN2'
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
