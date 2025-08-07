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
      title: Publications
      subtitle: Recent Research
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation
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
        
        <div class="contact-info">
          <span id="protected-email" 
                class="email-protected"
                title="Click to reveal email address">
            Click to reveal email
          </span>
        </div>
        
        **Academic Affiliation:** EPITA & IONIS Education Group, Paris, France
        
        **Research Areas:** Machine Learning, Deep Learning, Reinforcement Learning, NLP, Robotics
        
        Feel free to reach out for research collaborations, academic discussions, or inquiries about AI and machine learning projects.
        
        {{ partial "email_protection.html" . }}
    design:
      columns: '1'
      background:
        color: white
---
