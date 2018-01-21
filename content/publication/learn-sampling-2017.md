+++
title = "Online Learning to Sample"
#date  = "2016-03-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Guillaume Bouchard", "Théo Trouillon", "Julien Perez", "Adrien Gaidon"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "CoRR, Vol. abs/1506.09016, 2016"

# Abstract and optional shortened version.
abstract = "Stochastic Gradient Descent (SGD) is one of the most widely used techniques for online optimization in machine learning. In this work, we accelerate SGD by adaptively learning how to sample the most useful training examples at each time step. First, we show that SGD can be used to learn the best possible sampling distribution of an importance sampling estimator. Second, we show that the sampling distribution of an SGD algorithm can be estimated online by incrementally minimizing the variance of the gradient. The resulting algorithm - called Adaptive Weighted SGD (AW-SGD) - maintains a set of parameters to optimize, as well as a set of parameters to sample learning examples. We show that AWSGD yields faster convergence in three different applications: (i) image classification with deep features, where the sampling of images depends on their labels, (ii) matrix factorization, where rows and columns are not sampled uniformly, and (iii) reinforcement learning, where the optimized and exploration policies are estimated at the same time, where our approach corresponds to an off-policy gradient algorithm."


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "https://arxiv.org/abs/1506.09016"
url_preprint = "https://arxiv.org/abs/1506.09016"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

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
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.