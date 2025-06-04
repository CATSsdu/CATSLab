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
        left_info: |
          体系结构与可信系统（CA&TS）实验室，隶属于山东大学网络空间安全学院，研究领域囊括隐私计算的异构加速、系统设计及实时分析。

          年轻・自由・协作・创新。团队教师平均年龄不满35岁，学生平均年龄不满25岁。独立开放的个人课题，互惠互享的科研小组。

          聚焦前沿问题，推动技术落地。实验室在MICRO、ASPLOS、HPCA、RTSS等国际顶级会议上持续发表高水平论文，与华为、蚂蚁、字节等头部企业深度合作，科研成果在学术界和产业界均产生了广泛影响。

        right_info: |
          弹性工作时间，无打卡制度

          每学期至少一次大型团建，登山、轰趴、运动会...，自主策划，自由组织

          充足的科研经费支撑，国内领先、国际一流的软硬件条件

          国际化平台，合作者来自香港、新加坡、美国...，多名学生获推荐出国深造
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
          image:
            filename: front2.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#555'
      - title: 加入我们
        content: '在自由中研究，在研究中成长'
        align: right
        background:
          image:
            filename: front3.jpg
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
