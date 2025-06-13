---
title: ""   # leave empty to use site title
date: 2025-06-01
type: landing

design:
  spacing: "3rem"   

sections:
  - block: resume-biography-3
    content:
      username: admin   # display information from authors/admin/_index.md
      text: ""          # leave empty to use author bio
      button:
        text: Download CV
        url: uploads/LWH_CV_20250520.pdf
    design:
      css_style: custom  # I tried making my own but it wasn't
      background:
        image:          
          filename: banner.png # background image. you can do this for any of the blocks below, too
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
      css_style: custom
      spacing:
        padding: ['3rem', '0', '0', '0']
  - block: resume-experience
    content:
      username: admin
    design:
      date_format: 'January 2006' # Hugo date format
      is_education_first: false # Education or Experience section first?
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: true
  - block: collection
    id: news
    content:
      title: What I've been up to
      subtitle: '' # this did not seem to do anything
      text: ""
      page_type: post # page type to display. E.g. post, talk, publication...
      count: 5 # how many pages to display? 0 = all pages
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
      view: date-title-summary
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
  - block: collection
    id: talks
    content:
      title: Selected Presentations
      filters:
        folders:
          - event
        featured_only: true
    design:
      view: article-grid
      columns: 3
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: |-
        #### Philosophy
        
        I love learning about psychology, and this passion deeply informs my teaching. Beyond introductory courses, most students enroll in psychology classes because of genuine interest. The key challenge isn’t fostering interest but making the learning accessible and ensuring assignments clearly facilitate learning.

        Intrinsic motivation is essential yet challenging to cultivate. Thus, I strive to minimize barriers to learning by structuring both coursework and in-class activities optimally. Effective teaching requires more than clearly communicating course content; it demands creating engaging conditions that motivate students beyond the classroom. My approach emphasizes this often-overlooked element, leading to consistent positive outcomes, enthusiastic feedback, and enhanced student learning.

        #### Commitment to Diversity Equity & Inclusion

        I still distinctly recall my father, then a manager at General Motors Design, impressing upon me the importance of diversity for effective teamwork, problem-solving, and creativity. He emphasized that individual and team ideas are shaped and limited by upbringing and culture, and that diversity inherently broadens this scope, generating ideas that non-diverse teams might never consider. As psychologists, we recognize how deeply culture influences cognition at both individual and collective levels. Thus, the profound benefits of diversity in ideas, efficiency, and outcomes cannot be overstated.

        Beyond cognitive and creative advantages, I firmly believe in the importance of equity and inclusion to uplift and create opportunities for individuals from disadvantaged backgrounds—those who rarely encounter open doors of opportunity. As a white man from a privileged background, I’ve reflected deeply on the advantages that have brought me to where I am today, and I view it as my responsibility to leverage my position to empower and support those whose paths differ from mine.

        As an instructor and mentor, I am committed to fostering a safe, inclusive learning environment for students from all backgrounds. I actively strive to cultivate a sense of belonging and encourage the inclusion of diverse perspectives across race, ethnicity, gender identity, sexual orientation, age, socioeconomic status, disability, neurodiversity, religion, and national origin in psychology courses and research. Moreover, I am dedicated to making psychological knowledge and research accessible and beneficial to people of all backgrounds.
  - block: collection
    content:
      title: Courses
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      columns: 3
  - block: resume-awards
    id: recognition
    content:
      title: Funding & Recognition
      username: admin




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
