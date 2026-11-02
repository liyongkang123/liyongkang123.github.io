---
title: "On the Robustness of LLM-Based Dense Retrievers: A Systematic Analysis of Generalizability and Stability"
authors:
- admin
- Panagiotis Eustratiadis, Yixing Fan, Evangelos Kanoulas
date: "2026-04-17T00:00:00Z"
doi: "10.48550/arXiv.2604.16576"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-17T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2604.16576 (Under Review)"
publication_short: "**Preprint (Under Review)**"

abstract: Decoder-only large language models (LLMs) are increasingly replacing BERT-style architectures as the backbone for dense retrieval, achieving substantial performance gains and broad adoption. However, the robustness of these LLM-based retrievers remains underexplored. In this paper, we present the first systematic study of the robustness of state-of-the-art open-source LLM-based dense retrievers from two complementary perspectives: generalizability and stability. For generalizability, we evaluate retrieval effectiveness across four benchmarks spanning 30 datasets, using linear mixed-effects models to estimate marginal mean performance and disentangle intrinsic model capability from dataset heterogeneity. Our analysis reveals that while instruction-tuned models generally excel, those optimized for complex reasoning often suffer a ``specialization tax,'' exhibiting limited generalizability in broader contexts. For stability, we assess model resilience against both unintentional query variations~(e.g., paraphrasing, typos) and malicious adversarial attacks~(e.g., corpus poisoning). We find that LLM-based retrievers show improved robustness against typos and corpus poisoning compared to encoder-only baselines, yet remain vulnerable to semantic perturbations like synonymizing. Further analysis shows that embedding geometry (e.g., angular uniformity) provides predictive signals for lexical stability and suggests that scaling model size generally improves robustness. These findings inform future robustness-aware retriever design and principled benchmarking. Our code is publicly available at this https URL.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/abs/2604.16576
url_code: 'https://github.com/liyongkang123/Robust_LLM_Retriever_Eval'
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
