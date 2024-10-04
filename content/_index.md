---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-09-28
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
    
  - block: markdown
    content:
    text: |-
      <!-- HTML과 JavaScript를 이용한 슬라이더 -->
      <div id="customSlider" class="slider">
        <div class="slide">
          <img src="assets/media/Javice.jpg" alt="Javice" style="filter: brightness(0.4);">
          <div class="caption"><a href="https://jbnu-javice.github.io/">Javice - studying Web</a></div>
        </div>
        <div class="slide">
          <img src="assets/media/alps.jpg" alt="Alps" style="filter: brightness(0.4);">
          <div class="caption"><a href="https://sites.google.com/view/jbnu-alps">Alps - studying algorithm solving</a></div>
        </div>
        <div class="slide">
          <img src="assets/media/photobus.jpg" alt="Photobus" style="filter: brightness(0.4);">
          <div class="caption"><a href="http://www.jbnudongari.com/file/club_detail_view.php?cs_ancestor=2&cs_mkey=2&cateno=4&no=63">Photobus - studying photography</a></div>
        </div>
      </div>

      <style>
        /* 슬라이더 CSS */
        .slider { position: relative; width: 100%; overflow: hidden; }
        .slide { display: none; text-align: center; }
        .slide img { width: 100%; }
        .caption { position: absolute; bottom: 10px; color: #fff; background: rgba(0, 0, 0, 0.5); width: 100%; }
      </style>

      <script>
        let slideIndex = 0;
        showSlides();

        function showSlides() {
          const slides = document.getElementsByClassName("slide");
          for (let i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
          }
          slideIndex++;
          if (slideIndex > slides.length) { slideIndex = 1 }
          slides[slideIndex - 1].style.display = "block";
          setTimeout(showSlides, 3000); // 3초마다 전환
        }
      </script>

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

        I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
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
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
