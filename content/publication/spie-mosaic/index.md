---
title: "Deep learning based classification of morphological patterns in reflectance confocal microscopy to guide noninvasive diagnosis of melanocytic lesions"
date: 2017-01-28T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- Kivanc Kose
- admin
- Setareh Ariafar
- Christi Alessi-Fox
- Melissa Gill
- Jennifer Dy
- Dana H. Brooks
- Milind Rajadhyaksha

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
publication_types: ["0"]

# Publication name and optional abbreviated version.
publication: "In *SPIE Photonics West BioS 2017*"
publication_short: ""

# Abstract and optional shortened version.
abstract: "In this study we present a deep learning based classification algorithm for discriminating morphological patterns that appear in RCM mosaics of melanocytic lesions collected at the dermal epidermal junction (DEJ). These patterns are classified into 6 distinct types in the literature: background, meshwork, ring, clod, mixed, and aspecific. Clinicians typically identify these morphological patterns by examination of their textural appearance at 10X magnification. To mimic this process we divided mosaics into smaller regions, which we call tiles, and classify each tile in a deep learning framework. We used previously acquired DEJ mosaics of lesions deemed clinically suspicious, from 20 different patients, which were then labelled according to those 6 types by 2 expert users. We tried three different approaches for classification, all starting with a publicly available convolutional neural network (CNN) trained on natural image, consisting of a series of convolutional layers followed by a series of fully connected layers: (1) We fine-tuned this network using training data from the dataset. (2) Instead, we added an additional fully connected layer before the output layer network and then re-trained only last two layers, (3) We used only the CNN convolutional layers as a feature extractor, encoded the features using a bag of words model, and trained a support vector machine (SVM) classifier. Sensitivity and specificity were generally comparable across the three methods, and in the same ranges as our previous work using SURF features with SVM .  Approach (3) was less computationally intensive to train but more sensitive to unbalanced representation of the 6 classes in the training data. However we expect CNN performance to improve as we add more training data because both the features and the classifier are learned jointly from the data."

# Featured image thumbnail (optional)
image_preview: ""

# Is this a selected publication? (true/false)
selected: false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects: []

# Tags (optional).
#   Set `tags: []` for no tags, or use the form `tags: ["A Tag", "Another Tag"]` for one or more tags.
tags: []

# Links (optional).
url_pdf: ""
url_preprint: ""
url_code: ""
url_dataset: ""
url_project: ""
url_slides: "https://www.slideshare.net/secret/g03HFlMVoqL63J"
url_video: ""
url_poster: ""
url_source: ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom: [{name: "Custom Link", url: "http://example.org"}]

# Does the content use math formatting?
math: true

# Does the content use source code highlighting?
highlight: true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image: "example.jpg"`.
header:
  image: "banners/mosaic.png"
  caption: "Segmentations for 3 RCM mosaics"

---