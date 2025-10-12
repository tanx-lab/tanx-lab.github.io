---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown #hero
    content:
      title: |
        TanX Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **TanX-Lab** is a research group dedicated to advancing mechanical engineering and its applications in medicine. Our team investigates interdisciplinary problems at the interface of engineering and medicine, including drug delivery, circulating tumor cell detection, microfluidic device design, and thrombosis. We have developed an open-source large scale high performance computing framework for blood modeling consideirng the fluid solid interactions. 

        Our current research focuses on **physics-informed machine learning, multiscale modeling of blood flow, and inverse problems for design and optimization**.
  
  - block: collection
    content:
      title: Latest News
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
      page_type: post
    design:
      view: compact #card
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
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
