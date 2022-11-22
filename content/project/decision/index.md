---
title: Model-free decision boundary draw
summary: A model-free decision boundary draw method made by KNN.
tags:
  - Deep Learning
date: '2022-11-11T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
#  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - icon: zhihu
    icon_pack: fab
    name: Follow
    url: https://zhuanlan.zhihu.com/p/582307338
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Recently, we wanted to use Decision Boundary to represent the clustering results when carrying out the clustering task. I have tried several methods on the Internet, which either rely on the model decision (the data of we are of high dimension, so it is necessary to calculate the clustering result and then reduce the dimension, rather than cluster after reducing the dimension), or the realization like convex hull (some error points will be selected in the box). It can't meet the actual demand.


Therefore, KNeighbors is used to fit the boundary, and a model-free method of decision boundary drawing is implemented. Only the labels of data and prediction are provided to draw the boundary. And the smoothness of the boundary can be adjusted according to the k value.

More detail you can check in  {{< staticref "https://zhuanlan.zhihu.com/p/582307338" "newtab" >}}Blog{{< /staticref >}}.
