---
title: "A Multiresolution Convolutional Neural Network with Partial Label Training for Annotating Reflectance Confocal Microscopy Images of Skin"
date: 2018-08-23T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- admin
- Kivanc Kose
- Christi Alessi-Fox
- Melissa Gill
- Dana H. Brooks
- Jennifer G. Dy
- Milind Rajadhyaksha

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
publication: "In *21. International Conference On Medical Image Computing and Computer Assisted Intervention*"
publication_short: "In *MICCAI*"

# Abstract and optional shortened version.
abstract: "We describe a new multiresolution 'nested encoder-decoder' convolutional network architecture and use it to annotate morphological patterns in reflectance confocal microscopy (RCM) images of human skin for aiding cancer diagnosis. Skin cancers are the most common types of cancers, melanoma being the deadliest among them. RCM is an effective, non-invasive pre-screening tool for skin cancer diagnosis, with the required cellular resolution. However, images are complex, low-contrast, and highly variable, so that clinicians require months to years of expert-level training to be able to make accurate assessments. In this paper, we address classifying 4 key clinically important structural/textural patterns in RCM images. The occurrence and morphology of these patterns are used by clinicians for diagnosis of melanomas. The large size of RCM images, the large variance of pattern size, the large-scale range over which patterns appear, the class imbalance in collected images, and the lack of fully-labeled images all make this a challenging problem to address, even with automated machine learning tools. We designed a novel nested U-net architecture to cope with these challenges, and a selective loss function to handle partial labeling. Trained and tested on 56 melanoma-suspicious, partially labeled, 12k x 12k pixel images, our network automatically annotated diagnostic patterns with high sensitivity and specificity, providing consistent labels for unlabeled sections of the test images. Providing such annotation will aid clinicians in achieving diagnostic accuracy, and perhaps more important, dramatically facilitate clinical training, thus enabling much more rapid adoption of RCM into widespread clinical use process. In addition, our adaptation of U-net architecture provides an intrinsically multiresolution deep network that may be useful in other challenging biomedical image analysis applications. *First two authors share first authorship.*"


# Is this a selected publication? (true/false)
featured: false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects: []

# Links (optional).
url_pdf: "https://link.springer.com/chapter/10.1007/978-3-030-00934-2_33"
url_preprint: "https://arxiv.org/abs/1802.02213v2"
url_code: ""
url_dataset: ""
url_project: ""
url_slides: ""
url_video: ""
url_poster: "https://drive.google.com/open?id=1wtbiFOOqYRFFNjmbhDcKh8D-qvgYqZ0I"
url_source: ""

# Tags (optional).
#   Set `tags: []` for no tags, or use the form `tags: ["A Tag", "Another Tag"]` for one or more tags.
tags: ["RCM"]

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
  focal_point: "Center"

#header:
#  image: "banners/munet.png"

---
