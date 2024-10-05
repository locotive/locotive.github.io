---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-09-28
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      css_id: about-me
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: slider
    content:
      slides:
        - title: "<span style='font-size:70%'>club</span>"
          content: "<span style='font-size:70%'>동아리</span>"
          align: center
          background:
            image:
              filename: JBNU.png
              filters:
                brightness: 0.4
            position: center
            color: '#000'
            size: cover
        - title: "<span style='font-size:70%'>Javice</span>"
          content: "<span style='font-size:70%'>웹 스터디</span>"
          align: center
          background:
            image:
              filename: Javice.png
              filters:
                brightness: 0.4
            position: center
            color: '#000'
            size: cover
        - title: "<span style='font-size:70%'>alps</span>"
          content: "<span style='font-size:70%'>알고리즘 스터디</span>"
          align: center
          background:
            image:
              filename: alps.png
              filters:
                brightness: 0.4
            position: center
            color: '#000'
            size: cover
        - title: "<span style='font-size:70%'>photobus</span>"
          content: "<span style='font-size:70%'>사진 공부</span>"
          align: center
          background:
            image:
              filename: photobus.png
              filters:
                brightness: 0.4
            position: center
            color: '#000'
            size: cover
      design:
        slider:
          autoplay: true
          interval: 5000
          show_arrows: true
          show_dots: true  

  # Experience Section
  - block: resume-experience
    content:
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: false

  - block: collection
    content:
      title: Now Studying
      filters:
        folders:
          - studying
    design:
      view: community/custom_list
      columns: '3'

  - block: collection
    content:
      title: In Progress Projects
      filters:
        folders:
          - progress
    design:
      view: community/custom_single

  - block: collection
    content:
      title: completed Projects
      filters:
        folders:
          - completed
    design:
      view: date-title-summary
      columns: 3

  - block: collection
    content:
      title: planned Projects
      filters:
        folders:
          - planned
    design:
      view: article-grid
      columns: 3
---
