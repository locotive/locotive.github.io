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
      title: 기술 & 취미
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
        - title: "<span style='font-size:90%'>취미</span>"
          content: <span style="font-size:90%">저는 제 취미를 결합하여 프로젝트를 계획합니다.<span style="font-size:90%">
          align: center
          background:
            image:
              filename: hobby.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
        - title: "<span style='font-size:90%'>체스</span>"
          content: <span style="font-size:90%">집중력과 순간적인 판단력을 기릅니다.<span style="font-size:90%">
          align: center
          background:
            image:
              filename: chess.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
        - title: "<span style='font-size:90%'>LoLchess</span>"
          content: "<span style='font-size:90%'>집중력과 순간적인 판단력을 기릅니다.<span style='font-size:90%'>"
          align: center
          background:
            image:
              filename: LoLchess.jpg
              filters:
                brightness: 0.4
            position: center
            color: '#000'
          link:  # 버튼 추가
            url: "https://chzzk.naver.com/e9c11510c1c6097a20b92ebcb289b26a"  # 이동할 페이지 링크
            text: "Favorite"   # 버튼에 표시될 텍스트
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
          link:  # 버튼 추가
            url: "https://open.spotify.com/playlist/5St07oBQnCjp2MRDtu5jTr?si=74b97ff67c9e4b0d"  # 이동할 페이지 링크
            text: "Chill"   # 버튼에 표시될 텍스트
        - title: "<span style='font-size:90%'>사진 촬영</span>"
          content: "<span style='font-size:90%'>다양한 시각을 탐색합니다.</span>"
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
