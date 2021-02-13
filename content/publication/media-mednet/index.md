---
title: "Segmentation of Cellular Patterns in Confocal Images of Melanocytic Lesions in vivo via a Multiscale Encoder-Decoder Network (MED-Net)"
date: "2020-01-01T00:00:00"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- Kivanc Kose
- admin
- Christi Alessi-Fox
- Melissa Gill
- Caterina Longo
- Giovanni Pellacani
- Jennifer Dy
- Dana H. Brooks
- Milind Rajadhyaksha

# Author notes (optional)
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
publication_types: ["2"]

# Publication name and optional abbreviated version.
publication: In *Medical Image Analysis*
publication_short: In *MedIA*

# Abstract and optional shortened version.
abstract: In-vivo optical microscopy is advancing into routine clinical practice for non-invasively guiding diagnosis and treatment of cancer and other diseases, and thus beginning to reduce the need for traditional biopsy. However, reading and analysis of the optical microscopic images are generally still qualitative, relying mainly on visual examination. Here we present an automated semantic segmentation method called 'Multiscale Encoder-Decoder Network (MED-Net)' that provides pixel-wise labeling into classes of patterns in a quantitative manner. The novelty in our approach is the modeling of textural patterns at multiple scales. This mimics the procedure for examining pathology images, which routinely starts with low magnification (low resolution, large field of view) followed by closer inspection of suspicious areas with higher magnification (higher resolution, smaller fields of view). We trained and tested our model on non-overlapping partitions of 117 reflectance confocal microscopy (RCM) mosaics of melanocytic lesions, an extensive dataset for this application, collected at four clinics in the US, and two in Italy. With patient-wise cross-validation, we achieved pixel-wise mean sensitivity and specificity of 70±11% and 95±2%, respectively, with 0.71±0.09 Dice coefficient over six classes. In the scenario, we partitioned the data clinic-wise and tested the generalizability of the model over multiple clinics. In this setting, we achieved pixel-wise mean sensitivity and specificity of 74% and 95%, respectively, with 0.75 Dice coefficient. We compared MED-Net against the state-of-the-art semantic segmentation models and achieved better quantitative segmentation performance. Our results also suggest that, due to its nested multiscale architecture, the MED-Net model annotated RCM mosaics more coherently, avoiding unrealistic-fragmented annotations.


# Is this a selected publication? (true/false)
featured: true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects: []

# Tags (optional).
#   Set `tags: []` for no tags, or use the form `tags: ["A Tag", "Another Tag"]` for one or more tags.
tags: ["RCM"]

# Links (optional).
url_pdf: "https://www.sciencedirect.com/science/article/pii/S136184152030205X"
url_preprint: "https://arxiv.org/abs/2001.01005"
url_code: ""
url_dataset: ""
url_project: ""
url_slides: ""
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
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # Caption (optional)
  caption: ""
  preview_only: false
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: "Smart"

#[header]
#  image: "banners/vae.png"
---