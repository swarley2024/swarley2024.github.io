---
title: "Dual Adversarial Neural Transfer for Low-resource Named Entity Recognition"
authors:
- Joey Tianyi Zhou*
- Hao Zhang*
- Di Jing
- Hongyuan Zhu
- Rick Siow Mong Goh
- Kenneth Kwok
date: "2019-07-30T00:00:00Z"
doi: "10.18653/v1/P19-1336"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (ACL 2019)"
publication_short: "ACL 2019"

abstract: We propose a new neural transfer method termed Dual Adversarial Transfer Network (DATNet) for addressing low-resource Named Entity Recognition (NER). Specifically, two variants of DATNet, i.e., DATNet-F and DATNet-P, are investigated to explore effective feature fusion between high and low resource. To address the noisy and imbalanced training data, we propose a novel Generalized Resource-Adversarial Discriminator (GRAD). Additionally, adversarial training is adopted to boost model generalization. In experiments, we examine the effects of different components in DATNet across domains and languages, and show that significant improvement can be obtained especially for low-resource data, without augmenting any additional hand-crafted features and pre-trained language model.

# Summary. An optional shortened abstract.
# summary: 

tags:
# - Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.aclweb.org/anthology/P19-1336.pdf
url_code: https://github.com/26hzhang/DATNet
url_dataset: ''
url_poster: /files/DATNet-poster.pdf
url_project: ''
url_slides: /files/DATNet-slides.pdf
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---