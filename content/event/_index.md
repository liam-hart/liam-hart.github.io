---
# title: Presentations
# cms_exclude: true

# design:
#   # Section spacing
#   spacing: '5rem'

# # Page sections
# sections:
#   - block: collection
#     id: presentations
#     content:
#       title: Presentations
#       filters:
#         folders:
#           - event
#     design:
#       view: article-grid
#       columns: 3

# view: article-grid





title: Presentations
summary: My presentations
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    content:
      title: Presentations
      count: 0
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 3
---