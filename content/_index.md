---
title: ""
layout: landing

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/LWH_CV_20250520.pdf
        css_class: center-button
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: banner.png
          filters:
            brightness: .5
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        My research focuses on how our memory for meaningful life experiences is affected by aging. 
        
        I apply natural language processing to reveal how people narrate memories differently across different stages of the lifespan. This hybrid approach deals with the shortcomings and leverages the strengths of qualitative and quantitative methods.

        Please don't hesitate to reach out! I am always looking for more friends and collaborators 🤝

  # - block: collection
  #   id: papers
  #   content:
  #     title: Working Papers
  #     filters:
  #       folders:
  #         - papers
  #       featured_only: true
  #     design:
  #       view: citation

  # - block: collection
  #   id: papers
  #   conent:
  #     title: Publications
  #     filters:
  #       folders:
  #         - papers
  #       exclude_featured: true
  #     design:
  #       view: citation
---