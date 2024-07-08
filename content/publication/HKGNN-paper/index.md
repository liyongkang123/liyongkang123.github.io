---
title: "Hyper-relational knowledge graph neural network for next POI recommendation"
authors:
- Jixiao Zhang
- admin
- Ruotong Zou, Jingyuan Zhang,Renhe Jiang, Zipei Fan, Xuan Song
date: "2024-07-01T00:00:00Z"
doi: "10.1007/s11280-024-01279-y"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "World Wide Web 27, 46 (2024)"
publication_short: "**World Wide Web Journal**"

abstract: With the advancement of mobile technology, Point of Interest (POI) recommendation systems in Location-based Social Networks (LBSN) have brought numerous benefits to both users and companies. Many existing works employ Knowledge Graph (KG) to alleviate the data sparsity issue in LBSN. These approaches primarily focus on modeling the pair-wise relations in LBSN to enrich the semantics and thereby relieve the data sparsity issue. However, existing approaches seldom consider the hyper-relations in LBSN, such as the mobility relation (a 3-ary relation user-POI-time).  This makes the model hard to exploit the semantics accurately. In addition, prior works overlook the rich structural information inherent in KG, which consists of higher-order relations and can further alleviate the impact of data sparsity.To this end, we propose a Hyper-Relational Knowledge Graph Neural Network (HKGNN) model. In HKGNN, a Hyper-Relational Knowledge Graph (HKG) that models the LBSN data is constructed to maintain and exploit the rich semantics of hyper-relations. Then we proposed a Hypergraph Neural Network to utilize the structural information of HKG in a cohesive way. In addition, a self-attention network is used to leverage sequential information and make personalized recommendations. Furthermore, side information, essential in reducing data sparsity by providing background knowledge of POIs, is not fully utilized in current methods. In light of this, we extended the current dataset with available side information to further lessen the impact of data sparsity. Results of experiments on four real-world LBSN datasets demonstrate the effectiveness of our approach compared to existing state-of-the-art methods. Our implementation is available at https://github.com/aeroplanepaper/HKG.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://link.springer.com/article/10.1007/s11280-024-01279-y#citeas
url_code: 'https://github.com/aeroplanepaper/HKG'
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
