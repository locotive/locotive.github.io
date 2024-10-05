---
title: Completed Projects
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

# Optional header image (relative to `static/media/` folder).
sections:
  - block: collection
    content:
      title: Completed Projects
      text: ''
      filters:
        folders:
          - completed
    design:
      view: article-grid
      fill_image: false
      columns: 3
---