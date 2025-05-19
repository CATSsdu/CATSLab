---
title: Tour
date: 2022-10-24

type: landing

design:
  class: my-slider
  is_fullscreen: true
  loop: false
  interval: 2000
sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to CATS Lab
        content: Who we are...
        align: center
        background:
          image:
            filename: front.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: Moments
        align: left
        gallery:
          - filename: moment1.jpg
            class: tall
          - filename: moment2.jpg
            class: normal
          - filename: moment3.jpg
            class: normal
          - filename: moment5.jpg
            class: normal
          - filename: moment4.jpg
            class: wide

        background:
          position: center
          color: '#555'
      - title: Join us
        content: '在自由中研究，在研究中成长'
        align: right
        background:
          image:
            filename: front2.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---
