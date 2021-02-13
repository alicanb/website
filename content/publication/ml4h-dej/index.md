+++
title = "Delineation of Skin Strata in Reflectance Confocal Microscopy Images using Recurrent Convolutional Networks with Toeplitz Attention"
date = 2017-07-21T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin","K. Kose","J. Coll-Font","C. Alessi-Fox","D. H. Brooks","J. G. Dy","M. Rajadhyaksha"]


# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Machine learning for Health (ML4H) Workshop at NIPS 2017*"
publication_short = "In *ML4H*"

# Abstract and optional shortened version.
abstract = "Reflectance confocal microscopy (RCM) is an effective, non-invasive pre-screening tool for skin cancer diagnosis, but it requires extensive training and experience to assess accurately. There are few quantitative tools available to standardize image acquisition and analysis, and the ones that are available are not interpretable. In this study, we use a recurrent neural network with attention on convolutional network features. We apply it to delineate skin strata in vertically-oriented stacks of transverse RCM image slices in an interpretable manner. We introduce a new attention mechanism called Toeplitz attention, which constrains the attention map to have a Toeplitz structure. Testing our model on an expert labeled dataset of 504 RCM stacks, we achieve 88.17% image-wise classification accuracy, which is the current state-of-art."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["RCM"]

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/1712.00192"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "https://drive.google.com/open?id=18BbzDk-OoXmqUCqPnqF2xAWJqeF_KOdO"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "banners/dej-attention.png"
caption = "(Left to right) Maps for Global attention, Toeplitz Attention (D=7), Toeplitz Attention (D=1), Toeplitz Attention (D=0)"

+++