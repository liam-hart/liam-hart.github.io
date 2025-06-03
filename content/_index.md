---
title: ""   # leave empty to use site title
date: 2025-06-01
type: landing

design:
  spacing: "5rem"   

sections:
  - block: resume-biography-3
    content:
      username: admin   # display information from authors/admin/_index.md
      text: ""          # leave empty to use author bio
      button:
        text: Download CV
        url: uploads/LWH_CV_20250520.pdf
    design:
      css_class: dark
      background:
        color: black
        image:          # background image
          filename: banner.png
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
        I study how memory for meaningful life experiences changes with age. I am particulary focused on highly emotional events recalled in natural, narrative form.

        My research uses natural language processing (NLP) to examine how people narrate memories differently across the lifespan. By integrating qualitative depth with quantitative rigor, this mixed-methods approach leverages ecological validity and advancements in NLP to provide a more nuanced understanding of how we remember our lives.
    design:
      spacing:
        padding: ['100px', '0', '0px', '0']
  - block: collection
    id: papers
    content:
      title: Papers
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: ['100px', '0', '0px', '0']
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: card # card is only view available now, more may be added
      spacing:
        padding: ['100px', '0', '0px', '0']
  - block: collection
    id: news
    content:
      title: What I've been up to
      subtitle: '' # this did not seem to do anything
      text: ""
      page_type: post # page type to display. E.g. post, talk, publication...
      count: 10 # how many pages to display? 0 = all pages
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0 # offset by how many pages?
      order: desc # page order
    design:
      spacing:
        padding: ['100px', '0', '0px', '0']
    design:
      view: date-title-summary
      spacing:
        padding: ['100px', '0', '0px', '0']


# For showcasing featured publications, enabled with publications that have 'featured: true'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
---
