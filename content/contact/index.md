---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        欢迎报考山东大学网络空间安全学院的研究生和希望参与科研的本科生联系我们！

        招生条件：

          1、身体健康，有运动习惯，身体是革命的本钱。

          2、有一定抗压能力，不惧挑战。

          3、有自主意识，坚持独立思考，希望获得锻炼而非成绩，获得能力而非学历。

          4、拒绝三分钟热度。

      email: test@example.org
      phone: 888 888 88 88
      address:
        street: 滨海路72号山东大学K4
        city: Qingdao
        region: Shandong Province
        postcode: '266237'
        country: China
        country_code: CN
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
