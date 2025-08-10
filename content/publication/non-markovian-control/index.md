---
title: "Non-Markovian control using gated end-to-end memory policy networks"
authors:
- Julien Perez
- Fei Liu
date: "2017-01-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "CoRR, Vol. abs/1705.10993, 2017"
publication_short: "arXiv"

abstract: "Partially observable environments present an important open challenge in the domain of sequential control learning with delayed rewards. Despite numerous attempts during the two last decades, the majority of reinforcement learning algorithms and associated approximate models, applied to this context, still assume Markovian state transitions. In this paper, we explore the use of a recently proposed attention-based model, the Gated End-to-End Memory Network, for sequential control. We call the resulting model the Gated End-to-End Memory Policy Network. More precisely, we use a model-free value-based algorithm to learn policies for partially observed domains using this memory-enhanced neural network. This model is end-to-end learnable and it features unbounded memory. Indeed, because of its attention mechanism and associated non-parametric memory, the proposed model allows us to define an attention mechanism over the observation stream unlike recurrent models. We show encouraging results that illustrate the capability of our attention-based model in the context of the continuous-state non-stationary control problem of stock trading. We also present an OpenAI Gym environment for simulated stock exchange and explain its relevance as a benchmark for the field of non-Markovian decision process learning."

# Summary. An optional shortened abstract.
summary: Memory-augmented policy networks for non-Markovian control problems with external memory modules.

tags:
- Reinforcement Learning
- Non-Markovian Control
- Memory Networks
- Policy Gradients

featured: false

links: []
url_pdf: https://arxiv.org/pdf/1705.10993.pdf
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
