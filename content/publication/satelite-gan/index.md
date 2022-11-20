---
title: "Super-resolution reconstruction method for space target images based on dense residual block-based GAN"
authors:
- Hai-zhao Jing
- Jiang-lin Shi
- admin
- Yong Qi
- Wen-xiao Zhu
author_notes:
- ""
- ""
- "Equal contribution"
date: "2022-09-10T00:00:00Z"
doi: "10.37188/ope.20223017.2155"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Optics and Precision Engineering, 30*(17)"
publication_short: ""

abstract: To obtain the optical images of space targets with higher resolution and clarity， it is necessary to perform super-resolution reconstruction on the degraded images corrected by ground-based adaptive optics （AO） imaging telescopes. The image super-resolution reconstruction method based on deep learning has a fast operation speed and provides rich high-frequency detail information of the image； it has been widely used in natural， medical， and remote sensing images， among other applications. Aiming at the characteristics of spatial target AO images with a single background， limited resolution， motion blur， turbulent blur， and overexposure， this study proposes using a deep learning-based generative adversarial network （GAN） method to realize the super-resolution of spatial target AO images. For resolution reconstruction， a training set of spatial target AO simulation images is first constructed for neural network training， and a GAN super-resolution reconstruction method based on dense residual blocks is then proposed. By changing the traditional residual network to dense residual blocks， improving the network depth， and introducing a relative average loss function into the discriminator network， the discriminator becomes more robust， and the training of the generative adversarial network becomes more stable. Experiments show that the proposed method improves the peak-to-noise ratio （PSNR） and structural similarity index measure （SSIM） by more than 11.6% and 10.3%， respectively， compared with traditional interpolation super-resolution methods. In addition， it improves the PSNR and SSIM by 6.5% and 4.9% on average， respectively， compared with the deep learning-based blind image super-resolution method. The proposed method effectively realizes the clear reconstruction of a spatial target AO image， reduces the artifacts of the reconstructed image， enriches image details， and achieves a better reconstruction effect.

# Summary. An optional shortened abstract.
summary: To obtain the optical images of space targets with higher resolution and clarity， it is necessary to perform super-resolution reconstruction on the degraded images corrected by ground-based adaptive optics （AO） imaging telescopes.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
