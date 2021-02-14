---
title: "Deep Representation Learning for Complex Medical Images"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin


date: "2020-04-13T00:00:00Z"
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Ph.D. Thesis
publication_short:

abstract: "The performance of any task depends on the representation of the data. A good representation should capture the factors of variation relevant to the task at hand while discarding the nuisance variables. Since this is task-specific, the common way to build representations had been to hand-engineer them using domain knowledge. Since the advent of deep learning, this paradigm has shifted in favor of learning the representations in tandem with the task. Whereas there has been remarkable progress in representation learning with deep networks for natural images, medical images do not benefit from this paradigm as much as natural images. This is due to a number of factors particular to this domain, including relative data scarcity, class imbalance (e.g. many more “normal” images than abnormal or containing disease), and objects or patterns of interest occurring at multiple scales and without clear boundaries.  Another challenge for machine learning for medical images is that the tolerance for error is often lower compared to tasks involving natural images. As a result, representation learning for medical images still requires solutions that are tailored to the data and task at hand. 


In this thesis, we develop and study learning representations from complex medical data that enable high performance in several downstream tasks e.g., sequence classification and semantic segmentation. We then look at a more abstract deep learning methodology, generalization in Variational Autoencoders (VAEs), motivated by the limitations of current approaches, to improve our understanding of the relationship between available training data and representation of the more general population of images from which the training data were sampled.                   


The medical imaging modality we look at is Reflectance Confocal Microscopy (RCM), which is an effective, non-invasive pre-screening tool for skin cancer diagnosis. However, RCM images require extensive training and experience to assess accurately. There are few quantitative tools available to standardize image acquisition and analysis, and the available ones are not interpretable. In the first part of this work, we use a RNN with attention on CNN features to delineate in an interpretable manner the skin strata in vertically-oriented stacks of transverse RCM image slices. We introduce a new attention mechanism called Toeplitz attention, which constrains the attention map to have a Toeplitz structure. Testing our model on an expert-labeled dataset of 504 RCM stacks, we achieve 88.07% image-wise classification accuracy, which is the current state of the art.


In the second part of this work, we developed two automated semantic segmentation methods called MU-Net and MED-Net that provide pixel-wise labeling of RCM images into classes of cell structure patterns. The novelty in our approach is the modeling of textural patterns at multiple resolutions, mimicking the traditional procedure for examining pathology images, which routinely starts with low magnification (low resolution, large field of view) followed by closer inspection of suspicious areas with higher magnification (higher resolution, smaller fields of view). We trained and tested our model on non-overlapping partitions of 117 RCM mosaics of melanocytic lesions, an extensive dataset for this application, collected at four clinics in the US, and two in Italy. With patient-wise cross-validation, we achieved pixel-wise mean sensitivity and specificity of 70% and 95%, respectively, with a 0.71 Dice coefficient over six classes. In a second scenario, we partitioned the data by clinic or origin and tested the generalizability of the model across clinics. In this setting, we achieved pixel-wise mean sensitivity and specificity of 74% and 95%, respectively, with a 0.75 Dice coefficient. We compared MU-Net and MED-Net against the state-of-the-art semantic segmentation models and achieved better quantitative segmentation performance than previous approaches. Our results also suggest that, due to their nested multiscale architecture, our models annotated RCM mosaics more coherently, avoiding unrealistically fragmented annotations.


Last, we examine the generalization of the latent representations in VAEs. The VAE objective combines a reconstruction loss (the distortion) and a KL divergence term (the rate) that is often interpreted as a regularizer. Our work re-examines this view. We perform rate-distortion analyses in which we control the strength of the KL term, the network capacity, and the difficulty of the generalization problem. Lowering the coefficient of the KL term lowers generalization in low capacity models, but paradoxically improves generalization in higher capacity models. Moreover, in easier generalization tasks (where the training set examples closely approximate test set examples), lowering the coefficient even improves generalization in low capacity models. These results show that the KL term does not improve generalization in terms of reconstruction loss. This suggests future work to investigate what inductive biases can aid generalization in this class of models."


tags:
 - RCM
 - VAE

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: ProQuest
  url: 'https://search.proquest.com/openview/090e2163a36b083759928c078a09f3df/'

url_pdf: https://drive.google.com/file/d/1dA7atgh6_jvU3SOOZkHSZzbCqQhCYWdD/view?usp=sharing
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://drive.google.com/file/d/13qKIHXmiZG2vTk3VEmaC2bgAEjOIuaSY/view?usp=sharing'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} 

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
-->
