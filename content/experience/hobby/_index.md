---
title: 'hobby'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false

  - block: resume-languages
    content:
      title: Languages
      username: admin

  - block: slider
    content:
      slides:
        - title: "<span style="font-size:90%">Hobby</span>
          content: <span style="font-size:90%">I plan projects that combine my hobbies.<span style="font-size:90%">
          align: center
          background:
            image:
              filename: hobby.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
        - title: "<span style="font-size:90%">Chess</span>
          content: <span style="font-size:90%">Improvement in concentration and quick decision-making.<span style="font-size:90%">
          align: center
          background:
            image:
              filename: chess.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
        - title: "<span style='font-size:90%'>LoLchess</span>"
          content: "<span style='font-size:90%'>Improvement in concentration and quick decision-making.</span style="font-size:90%">"
          align: center
          background:
            image:
              filename: LoLchess.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
        - title: "<span style='font-size:90%'>Listening to music</span>"
          content: "<span style='font-size:90%'>I do a lot of coding work while listening to music.</span>"
          align: center
          background:
            image:
              filename: music.png
              filters:
                brightness: 0.4
            position: center
            color: '#000'
        - title: "<span style='font-size:90%'>Photography</span>"
          content: "<span style='font-size:90%'>Exploring different perspectives</span>"
          align: center
          background:
            image:
              filename: photo.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
      design:
        slider:
          autoplay: true
          interval: 5000
          show_arrows: true
          show_dots: true  
---
