---
title: In Progress Projects
type: landing
featured:
  image: luca-bravo-XJXWbfSo2f0-unsplash.jpg

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

# Optional header image (relative to `static/media/` folder).
sections:
  - block: collection
    content:
      title: In Progress Projects
      filters:
        folders:
          - progress
    design:
      view: article-grid
      fill_image: false
      columns: 1
---