---
title: "Less is More: Adaptive Prompt Compression and Exemplar Selection for Efficient Few-Shot Sentiment Analysis"

authors:
- Peter Atandoh
- admin
- Weikang Guo, Jinyu Guo, Jie Zou

# Author notes (optional)
 

date: "2026-03-10T00:00:00Z"
doi: " " 

# Schedule page publish date (NOT publication's date).
publishDate: "2026-03-16T00:00:00Z"

track: Journal paper

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Expert Systems With Applications"
publication_short: "**ESWA Journal**"

abstract: Few-shot sentiment analysis remains challenging due to limited labeled data and inefficient prompt design for large language models (LLMs). Existing prompting methods often rely on static exemplars and verbose inputs, leading to redundant tokens, higher inference cost, and limited generalization. Moreover, prior work typically improves exemplar selection or prompt compression in isolation, without explicitly balancing predictive accuracy and token efficiency under resource constraints. This study addresses two key challenges:(1) how to adaptively select semantically diverse and task-relevant exemplars, and (2) how to compress prompts while preserving sentiment-critical information under realistic resource constraints. We propose SRC3, a unified closed-loop prompt optimization framework that integrates Semantic embedding clustering, Reward-guided adaptive exemplar memory, and ClarityCore Compression prompting into a cost-aware inference-time policy for black-box LLMs. The semantic clustering module selects diverse exemplars by reweighting embeddings via uncertainty and novelty. The rewardguided exemplar mechanism updates exemplar utility through temporally smoothed feedback. ClarityCore applies deterministic TF-IDFbased compression to preserve sentiment-relevant cues while exposing a measurable compression ratio, which is incorporated into a reinforcement-inspired cost-aware objective. This coupling forms a feedback loop linking exemplar diversity, compression control, and reward optimization. Experiments on six benchmark sentiment datasets show that SR-C3 consistently improves accuracy while reducing latency and token cost, achieving superior performance–efficiency trade-offs over existing prompting baselines. These results position SR-C3 as a scalable and adaptive framework for resource-constrained few-shot sentiment analysis.
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
