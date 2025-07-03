---
title: "Rethinking the Privacy of Text Embeddings: A Reproducibility Study of “Text Embeddings Reveal (Almost) As Much As Text”"

authors:
- Dominykas Seputis
- admin
- Karsten	Langerak, Serghei	Mihailov

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: "2025-06-05T00:00:00Z"
doi: "" 

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-05T00:00:00Z"

track: Reproducibility paper

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "The ACM Conference on Recommender Systems (RecSys 2025)"
publication_short: "**RecSys2025(Reproducibility Paper, Oral)**"

abstract: Text embeddings are fundamental to many natural language processing~(NLP) tasks, extensively applied in domains such as recommendation systems and information retrieval~(IR). Traditionally, transmitting embeddings instead of raw text has been seen as privacy-preserving. However, recent methods such as Vec2Text challenge this assumption by demonstrating that controlled decoding can successfully reconstruct original texts from black-box embeddings. The unexpectedly strong results reported by Vec2Text motivated us to conduct further verification, particularly considering the typically non-intuitive and opaque structure of high-dimensional embedding spaces. In this work, we reproduce the Vec2Text framework and evaluate it from two perspectives, (1) validating the original claims, and (2) extending the study through targeted experiments. First, we successfully replicate the original key results in both in-domain and out-of-domain settings, with only minor discrepancies arising due to missing artifacts, such as model checkpoints and dataset splits. Furthermore, we extend the study by conducting a parameter sensitivity analysis, evaluating the feasibility of reconstructing sensitive inputs (e.g., passwords), and exploring embedding quantization as a lightweight privacy defense. Our results show that Vec2Text is effective under ideal conditions, capable of reconstructing even password-like sequences that lack clear semantics. However, we identify key limitations, including its sensitivity to input sequence length. We also find that Gaussian noise and quantization techniques can mitigate the privacy risks posed by Vec2Text, with quantization offering a simpler and more widely applicable solution. Our findings emphasize the need for caution in using text embeddings and highlight the importance of further research into robust defense mechanisms for NLP systems.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: ''
url_code: ''
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
