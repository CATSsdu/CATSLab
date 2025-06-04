---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        <span class="small-title">SDU Computer Architecture and Trustworthy System Lab</span>
      # image:
      #   filename: welcome.jpg
      text: |
        <span class="small-text">
          <br>
          山东大学体系结构和可信系统实验室是由鞠雷教授成立并领导的研究团队，现有教师4人，硕博研究生共43人。实验室近三年共发表CCF-A类论文16篇，获得2022年度CCF全国定制计算算法实现挑战赛冠亚军，2022年“华为杯”中国研究生网络安全创新大赛一等奖。实验室累计培养硕博研究生14人，毕业生去向包括蚂蚁研究院、华为2012实验室等。
        </span>
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'

  - block: collection
    content:
      title: Research Field
      subtitle: 
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: researchfield
    design:
      view: showcase
      columns: '1'

  - block: collection
    content:
      title: Technical Supports
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: support
    design:
      view: showcase
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
