---
title: "Structured Disentagled Representations"

authors:
- B. Esmaeili
- H. Wu
- S. Jain
- admin
- N. Siddarth
- B. Paige
- J. G. Dy
- D. H. Brooks
- J. W. van de Meent

date: "2019-04-04T00:00:00"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of the 22nd International Conference on Artificial Intelligence and Statistics 2019, Naha, Okinawa, Japan. PMLR: Volume 89"
publication_short: "In *AISTATS*"


abstract: Deep latent-variable models learn representations of high-dimensional data in an unsupervised manner. A number of recent efforts have focused on learning representations that disentangle statistically independent axes of variation by introducing modifications to the standard objective function. These approaches generally assume a simple diagonal Gaussian prior and as a result are not able to reliably disentangle discrete factors of variation. We propose a two-level hierarchical objective to control relative degree of statistical independence between blocks of variables and individual variables within blocks. We derive this objective as a generalization of the evidence lower bound, which allows us to explicitly represent the trade-offs between mutual information between data and representation, KL divergence between representation and prior, and coverage of the support of the empirical data distribution. Experiments on a variety of datasets demonstrate that our objective can not only disentangle discrete variables, but that doing so also improves disentanglement of other variables and, importantly, generalization even to unseen combinations of factors.

# Summary. An optional shortened abstract.
summary: ""

tags:
- VAE
featured: false

links:
- name: Preprint
  url: https://arxiv.org/abs/1804.02086
- name: Supplementary
  url: http://proceedings.mlr.press/v89/esmaeili19a/esmaeili19a-supp.pdf
url_pdf: http://proceedings.mlr.press/v89/esmaeili19a/esmaeili19a.pdf
url_code: ''
url_dataset: ''
url_poster: https://drive.google.com/open?id=1dUnnsH9r5J17aGKLq-VSU7uzG45IwiOI
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

#header:
#- image: "banners/hfvae.png"
---