---
title: "Online Learning to Sample"
authors:
- Guillaume Bouchard
- Théo Trouillon
- Julien Perez
- Adrien Gaidon
date: "2016-01-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2016-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "CoRR, Vol. abs/1506.09016, 2016"
publication_short: "arXiv"

abstract: "Stochastic Gradient Descent (SGD) is one of the most widely used techniques for online optimization in machine learning. In this work, we accelerate SGD by adaptively learning how to sample the most useful training examples at each time step. First, we show that SGD can be used to learn the best possible sampling distribution of an importance sampling estimator. Second, we show that the sampling distribution of an SGD algorithm can be estimated online by incrementally minimizing the variance of the gradient. The resulting algorithm - called Adaptive Weighted SGD (AW-SGD) - maintains a set of parameters to optimize, as well as a set of parameters to sample learning examples. We show that AWSGD yields faster convergence in three different applications: (i) image classification with deep features, where the sampling of images depends on their labels, (ii) matrix factorization, where rows and columns are not sampled uniformly, and (iii) reinforcement learning, where the optimized and exploration policies are estimated at the same time, where our approach corresponds to an off-policy gradient algorithm."

# Summary. An optional shortened abstract.
summary: Novel adaptive sampling technique for SGD that learns optimal sampling distributions to accelerate convergence.

tags:
- Stochastic Gradient Descent
- Optimization
- Sampling
- Machine Learning

featured: false

links: []
url_pdf: https://arxiv.org/pdf/1506.09016.pdf
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
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---
