---
title: "SLIM: Skill Learning with Multiple Critics"
authors:
- David Emukpere
- Bingbing Wu
- Julien Perez
- Jean-Michel Renders
date: "2024-02-01"
doi: "10.48550/arXiv.2402.00823"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-01T00:00:00Z"

publication_types: ["article"]

publication: "IEEE International Conference on Robotics and Automation (ICRA), 2024; also arXiv:2402.00823"
publication_short: "ICRA 2024"

abstract: "Self-supervised skill learning aims to acquire useful behaviors that leverage the underlying dynamics of the environment. Latent variable models, based on mutual information maximization, have been successful in this task but still struggle in the context of robotic manipulation. As it requires impacting a possibly large set of degrees of freedom composing the environment, mutual information maximization fails alone in producing useful and safe manipulation behaviors. Furthermore, tackling this by augmenting skill discovery rewards with additional rewards through a naive combination might fail to produce desired behaviors. To address this limitation, we introduce SLIM, a multi-critic learning approach for skill discovery with a particular focus on robotic manipulation. Our main insight is that utilizing multiple critics in an actor-critic framework to gracefully combine multiple reward functions leads to a significant improvement in latent-variable skill discovery for robotic manipulation while overcoming possible interference occurring among rewards which hinders convergence to useful skills. Furthermore, in the context of tabletop manipulation, we demonstrate the applicability of our novel skill discovery approach to acquire safe and efficient motor primitives in a hierarchical reinforcement learning fashion and leverage them through planning, significantly surpassing baseline approaches for skill discovery."

summary: Multi-critic actor-critic approach that combines multiple reward functions to discover safe, useful robotic manipulation skills.

tags:
- Reinforcement Learning
- Skill Discovery
- Robotics
- Manipulation

featured: false

image:
  caption: ''
  focal_point: ""
  preview_only: false

projects: []
slides: ""

links:
- name: arXiv
  url: https://arxiv.org/abs/2402.00823
url_pdf: 'https://arxiv.org/pdf/2402.00823'
---
