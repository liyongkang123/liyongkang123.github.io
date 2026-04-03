---
title: "Lost in Decoding? Reproducing and Stress-Testing the Look-Ahead Prior in Generative Retrieval"

authors:
- Kidist Amde Mekonnen
- admin
- Yubao Tang, Simon Lupart, Maarten de Rijke

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: "2026-04-03T00:00:00Z"
doi: " " 

# Schedule page publish date (NOT publication's date).
publishDate: "2026-04-03T00:00:00Z"

track: Reproducibility paper

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "The 49th International ACM SIGIR Conference on Research and Development in Information Retrieval"
publication_short: "**SIGIR2026(Reproducibility Paper, Oral)**"

abstract: Generative retrieval (GR) ranks documents by autoregressively generating identifiers. Trie-constrained beam search, which is used by many GR methods, is susceptible to early pruning of relevant prefixes. Planning ahead in generative retrieval (PAG) mitigates such prefix pruning by using simultaneous decoding to compute a document-level look-ahead prior that guides subsequent sequential decoding. We reproduce PAG at inference time and stress-test its decoding behavior. Using the authors’ released checkpoint and identifier/trie artifacts in the reported decoding setup, we reproduce the main effectiveness results on MS~MARCO Dev and TREC-DL 2019/2020 and corroborate the reported beam-size and latency trade-offs in our hardware setup. Beyond reproduction, we introduce plan drift diagnostics that quantify how intent-preserving query variations, including misspellings, reordering, synonym substitutions, paraphrases, naturality shifts, and translation-based variants, change the planner’s top-n candidate set and highest-weight tokens. We find that the planning signal is brittle, intent-preserving typos cause ``plan collapse,'' where the look-ahead bonus effectively vanishes, reverting the model to a weaker unguided search. We further evaluate cross-lingual robustness by querying a fixed English index with non-English \textsc{mMARCO} inputs, and assess inference-time mitigations and query-side adaptation that require no re-indexing. We reproduce PAG's reported effectiveness and confirm the benefit of planning-guided decoding, while showing that the planner's sparse token-level scoring mechanism is sensitive to query surface-form variation, a robustness aspect not systematically evaluated in the original work.
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
