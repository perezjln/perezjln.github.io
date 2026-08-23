---
title: "Learning Visual Representations with Caption Annotations"
authors:
- M.B. Sariyildiz
- Julien Perez
- D. Larlus
date: "2020-01-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Computer Vision"
publication_short: "ECCV 2020"

abstract: "Pretraining general-purpose visual features has become a crucial part of tackling many computer vision tasks. While one can learn such features on the extensively-annotated ImageNet dataset, recent approaches have looked at ways to allow for noisy, fewer, or even no annotations to perform such pretraining. Starting from the observation that captioned images are easily crawlable, we argue that this overlooked source of information can be exploited to supervise the training of visual representations. To do so, motivated by the recent progresses in language models, we introduce image-conditioned masked language modeling (ICMLM) -- a proxy task to learn visual representations over image-caption pairs. ICMLM consists in predicting masked words in captions by relying on visual cues. To tackle this task, we propose hybrid models, with dedicated visual and textual encoders, and we show that the visual representations learned as a by-product of solving this task transfer well to a variety of target tasks. Our experiments confirm that image captions can be leveraged to inject global and localized semantic information into visual representations."

# Summary. An optional shortened abstract.
summary: Novel approach for learning visual representations using caption annotations for improved visual understanding.

tags:
- Computer Vision
- Visual Representations
- Caption Learning
- Deep Learning
- Multimodal Learning
- Natural Language Processing
- Self-Supervised Learning
- Transfer Learning
- Semantic Understanding

keywords:
- "Computer Vision"
- "Visual Representations"
- "Caption Learning"
- "Deep Learning"
- "Multimodal Learning"
- "Natural Language Processing"
- "Self-Supervised Learning"
- "Transfer Learning"
- "Semantic Understanding"
- "Vision-Language Models"
- "ECCV"

featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
