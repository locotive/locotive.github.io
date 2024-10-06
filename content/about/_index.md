---
title: ""
date: 2024-09-28
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/empty.pdf
    design:
      css_class: dark

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
---