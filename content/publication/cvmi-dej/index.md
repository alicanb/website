---
title: "Delineation of Skin Strata in Reflectance Confocal Microscopy Images With Recurrent Convolutional Networks"
date: 2017-07-21T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- admin
- Trevor Gale
- Kivanc Kose
- Christi Alessi-Fox
- Dana H. Brooks
- Milind Rajadhyaksha
- Jennifer Dy


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
publication: "In *The IEEE Conference on Computer Vision and Pattern Recognition (CVPR) Workshops*"
publication_short: "In *CVMI*"

# Abstract and optional shortened version.
abstract: "Reflectance confocal microscopy (RCM) is an effective, non-invasive pre-screening tool for cancer diagnosis. However, acquiring and reading RCM images requires extensive training and experience, and novice clinicians exhibit high variance in diagnostic accuracy. Consequently, there is a compelling need for quantitative tools to standardize image acquisition and analysis. In this study, we use deep recurrent convolutional neural networks to delineate skin strata in stacks of RCM images collected at consecutive depths. To perform diagnostic analysis, clinicians collect RCM images at 4-5 specific layers in the tissue. Our model automates this process by discriminating between RCM images of different layers. Testing our model on an expert labeled dataset of 504 RCM stacks, we achieve 87.97% classification accuracy, and 9-fold reduction in the number of anatomically impossible errors compared to the previous state-of-the-art."

# Featured image thumbnail (optional)
image_preview: ""

# Is this a selected publication? (true/false)
selected: false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects: []

# Tags (optional).
#   Set `tags: []` for no tags, or use the form `tags: ["A Tag", "Another Tag"]` for one or more tags.
tags: ["RCM"]

# Links (optional).
url_pdf: "http://openaccess.thecvf.com/content_cvpr_2017_workshops/w8/html/Bozkurt_Delineation_of_Skin_CVPR_2017_paper.html"
url_preprint: ""
url_code: ""
url_dataset: ""
url_project: ""
url_slides: "https://www.slideshare.net/secret/177naL6wOJEMc6"
url_video: ""
url_poster: ""
url_source: ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom: [{name: "Custom Link", url: "http://example.org"}]

# Does the content use math formatting?
math: true

# Does the content use source code highlighting?
highlight: true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image: "example.jpg"`.
header:
  image: "banners/dej.gif"
  caption: "(Left) Full sequence RCN (Right) Classification of a stack"

---