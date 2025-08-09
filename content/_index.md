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
      subtitle: Latest research highlights
      filters:
        folders: [publication]
      count: 6
      sort_by: date
      sort_ascending: false
    design:
      view: date-title-summary
      columns: 1
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
      view: card
      columns: 1
      background:
        color: white
  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        - Email: <span id="protected-email" class="email-protected">Click to reveal</span>
        - Affiliation: EPITA | IONIS Education Group (Paris, France)
        - Areas: ML, DL, RL, NLP, Robotics

        Connect:
        - [Google Scholar](https://scholar.google.fr/citations?user=XneKjCsAAAAJ)
        - [LinkedIn](https://www.linkedin.com/in/julien-perez)
        - [GitHub](https://github.com/perezjln)
    design:
      columns: 1
      background:
        color: white
---
