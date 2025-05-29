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
    design:
      css_style: custom
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: new-river.png
          filters:
            brightness: .4
          size: cover
          position: center
          parallax: true

  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        My research focuses on how our memory for meaningful life experiences is affected by aging. 
        
        I apply natural language processing to reveal how people narrate memories differently across different stages of the lifespan. This hybrid approach deals with the shortcomings and leverages the strengths of qualitative and quantitative methods.

        Please don't hesitate to reach out! I am always looking for more friends and collaborators 🤝
    design:
      spacing:
        padding: ['100px', '0', '0px', '0']

  - block: resume-experience
    content:
      username: admin
    design:
      spacing:
        padding: ['100px', '0', '0px', '0']
      date_format: 'January 2006'
      is_education_first: false

  # - block: collection
  #   id: papers
  #   content:
  #     title: Working Papers
  #     filters:
  #       folders:
  #         - papers
  #       featured_only: true
  #   design:
  #     spacing:
  #       padding: ['100px', '0', '0px', '0']
  #     view: citation

  # - block: collection
  #   id: papers
  #   content:
  #     title: Publications
  #     filters:
  #       folders:
  #         - papers
  #       exclude_featured: true
  #   design:
  #     spacing:
  #       padding: ['100px', '0', '0px', '0']
  #     view: citation

  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      spacing:
        padding: ['100px', '0', '0px', '0']    

  - block: resume-awards
    content:
      title: Awards
      username: admin
    design:
      spacing:
        padding: ['100px', '0', '0px', '0']  
---