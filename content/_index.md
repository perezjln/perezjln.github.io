---
# Leave the homepage title empty to use the site title
title: ""
description: "Julien Perez - Full Professor specializing in Machine Learning, Deep Learning, Reinforcement Learning, Natural Language Processing, and AI Research at EPITA and IONIS Education Group"
keywords:
  - "Machine Learning"
  - "Deep Learning"
  - "Reinforcement Learning"
  - "Natural Language Processing"
  - "Dialog Systems"
  - "AI Research"
  - "Computer Science Professor"
  - "EPITA"
  - "IONIS"
  - "Julien Perez"
date: 2022-10-24
type: landing

# SEO settings
cascade:
  featured_image: "avatar.jpg"

design:
  # Default section spacing
  spacing: "3rem"

sections:
  - block: resume-biography
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      background:
        color: white
        text_color_light: false
  - block: collection
    id: publications
    content:
      title: Recent Publications
      subtitle: Latest Research in AI, Machine Learning, and Robotics
      text: |-
        **Recent Highlights:**
        
        ### 2025
        **AKD: Adversarial Knowledge Distillation For Large Language Models Alignment on Coding tasks** | *Large Language Models, Knowledge Distillation, Code Generation*
        
        ### 2024
        **Unsupervised Skill Discovery for Robotic Manipulation through Automatic Task Generation** | *Robotics, Skill Discovery, Manipulation*
        
        **SLIM: Skill Learning with Multiple Critics** | *Reinforcement Learning, Multi-Critic Networks*
        
        **DiffVersify: a Scalable Approach to Differentiable Pattern Mining** | *Pattern Mining, Deep Learning*
        
        ### 2023
        **Safety‑Aware Unsupervised Skill Discovery** | *Safe AI, Skill Learning, Robotics*
        
        **LARG, Language‑based Automatic Reward and Goal Generation** | *NLP, Reward Learning, Language Models*
        
        ### Key Research Areas:
        - **Machine Learning & Deep Learning:** Neural networks, optimization, representation learning
        - **Reinforcement Learning:** Policy learning, skill discovery, safe AI, robotics control
        - **Natural Language Processing:** Dialog systems, language models, text understanding
        - **Computer Vision:** Visual representations, multimodal learning, robotics perception
        - **Robotics:** Manipulation, locomotion, adaptive control systems
        
        [View All Publications →](/publication/)
      filters:
        folders:
          - publication
        featured_only: true
        exclude_featured: false
      design:
        view: citation
        columns: 1
    design:
      view: list
      background:
        color: white
  - block: collection
    id: teaching
    content:
      title: Teaching
      subtitle: Courses and Education
      filters:
        folders:
          - teaching
    design:
      view: list
      columns: 1
      background:
        color: white
  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        **Professional Contact:**
        
        📧 **Email:** julien.perez@epita.fr
        
        **Academic Affiliation:** EPITA | IONIS Education Group, Paris, France
        
        **Research Areas:** Machine Learning, Deep Learning, Reinforcement Learning, NLP, Robotics
        
        Feel free to reach out for research collaborations, academic discussions, or inquiries about AI and machine learning projects.
        
        **Connect with me:**
        - [Google Scholar](https://scholar.google.fr/citations?user=XneKjCsAAAAJ)
        - [LinkedIn](https://www.linkedin.com/in/julien-perez)
        - [GitHub](https://github.com/perezjln)
    design:
      columns: '1'
      background:
        color: white
---
