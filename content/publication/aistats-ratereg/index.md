---
title: "Rate-Regularization and Generalization in VAEs"
date: 2021-01-11T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
  - admin
  - Babak Esmaeili
  - Jean-Baptiste Tristan
  - Jennifer Dy
  - Dana H. Brooks
  - Jan-Willem van de Meent

author_notes:
- "Equal contribution"
- "Equal contribution"

# Publication type.
# Legend:
# 0: Uncategorized
# 1: Conference paper
# 2: Journal article
# 3: Preprint / Working Paper
# 4: Report
# 5: Book
# 6: Book section
# 7: Thesis
# 8: Patent
publication_types: ["1"]

# Publication name and optional abbreviated version.
publication: In *Proceedings of The 24th International Conference on Artificial Intelligence and Statistics, PMLR 130:3880-3888, 2021.*
publication_short: In *AISTATS*

# Abstract and optional shortened version.
abstract: "Variational autoencoders (VAEs) optimize an objective that comprises a reconstruction loss (the distortion) and a KL term (the rate). The rate is an upper bound on the mutual information, which is often interpreted as a regularizer that controls the degree of compression. We here examine whether inclusion of the rate term also improves generalization. We perform rate-distortion analyses in which we control the strength of the rate term, the network capacity, and the difficulty of the generalization problem. Lowering the strength of the rate term paradoxically improves generalization in most settings, and reducing the mutual information typically leads to underfitting. Moreover, we show that generalization performance continues to improve even after the mutual information saturates, indicating that the gap on the bound (i.e. the KL divergence relative to the inference marginal) affects generalization. This suggests that the standard spherical Gaussian prior is not an inductive bias that typically improves generalization, prompting further work to understand what choices of priors improve generalization in VAEs."


# Is this a selected publication? (true/false)
featured: true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects: []

# Tags (optional).
#   Set `tags: []` for no tags, or use the form `tags: ["A Tag", "Another Tag"]` for one or more tags.
tags: ['VAE']

# Links (optional).
url_pdf: "http://proceedings.mlr.press/v130/bozkurt21a.html"
url_preprint: "https://arxiv.org/abs/1911.04594"
url_code: ""
url_dataset: "https://github.com/neu-pml/tetrominoes"
url_project: ""
url_slides: ""
url_video: ""
url_poster: "https://drive.google.com/file/d/1EOlT5em5PyjCqJY45dnEfJwBaDSL8JvD/view?usp=sharing"
url_source: ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom: [{name: "Custom Link", url: "http://example.org"}]

# Does the content use math formatting?
math: true

# Does the content use source code highlighting?
highlight: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # Caption (optional)
  caption: ""
  preview_only: false
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: "Top"

---