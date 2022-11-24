---
title: "Extracting Fingerprint Features Using Autoencoder Networks for Gender Classification"
authors:
- Yong Qi
- admin
- He-fei-fei Jing
- Fei-yang Wang
author_notes:
- 
- "First Student Author"
date: "2022-09-15T00:00:00Z"
doi: "10.3390/app121910152"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Applied Sciences, 12*(19)"
publication_short: "***SCI Q2, IF:2.838***"

abstract: The fingerprint is an important biological feature of the human body, which contains abundant biometric information. At present, the academic exploration of fingerprint gender characteristics is generally at the level of understanding, and the standardization research is quite limited. A robust approach is presented in this article, Dense Dilated Convolution ResNet Autoencoder, to extract valid gender information from fingerprints. By replacing the normal convolution operations with the atrous convolution in the backbone, prior knowledge is provided to keep the edge details, and the global reception field can be extended. The results were explored from three aspects  (1) Efficiency of DDC-ResNet. We conducted experiments using a combination of 6 typical automatic feature extractors with 9 classifiers for a total of 54 combinations are evaluated in our dataset; the experimental results show that the combination of methods we used achieved an average accuracy of 96.5%, with a classification accuracy of 97.52% for males and 95.48% for females, which outperformed the other experimental combinations. (2) The effect of the finger. The results showed that the right ring finger was the most effective for finger classification by gender. (3) The effect of specific features. We used the Class Activating Mapping method to plot fingerprint concentration thermograms, which allowed us to infer that fingerprint epidermal texture features are related to gender. The results demonstrated that autoencoder networks are a powerful method for extracting gender-specific features to help hide the privacy information of the user’s gender contained in the fingerprint. Our experiments also identified three levels of features in fingerprints that are important for gender differentiation, including loops and whorls shape, bifurcations shape, and line shapes.

# Summary. An optional shortened abstract.
summary: |
      1. Investigated the effect of fingers by using separate fingers for gender classification and found that the best performing finger was the right ring finger, which achieved an accuracy of 92.455%
      2. Compared with six typical automatic feature extraction methods coupled with nine classifiers are evaluated in our dataset
      3. Exploded the impact of features by visualizing the concentration of fingerprints. According to the analysis, annular/angular (primary), divergent (secondary) and linear (tertiary) may be closely related to gender.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://drive.google.com/file/d/1MjfihpXXBbRlgUBkLlVM1vUCxBBIvoiB/view?usp=share_link
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
# slides: example
---

