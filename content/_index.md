---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: slider
  #   content:
  #     slides:
  #     - title: Patient-specific Blood Flow Modeling
  #       content: Retina
  #       align: center
  #       background:
  #         image:
  #           filename: retina_art.jpg
  #           filters:
  #             brightness: 0.7
  #         position: center
  #         color: '#555'
  #       link:
  #         text: Read more
  #         url: https://doi.org/10.1063/10.0010412
  #     - title: Microfluidic Design for Cancer Cell Detection
  #       content: Circulating tumore cell detection
  #       align: center
  #       background:
  #         image:
  #           filename: CTC_art.JPG
  #           filters:
  #             brightness: 0.7
  #         position: center
  #         color: '#555'
  #       link:
  #         # icon: graduation-cap
  #         # icon_pack: fas
  #         text: Read more
  #         url: https://www.youtube.com/watch?v=bCsn95v3rC4
  #     - title: Granular Flow
  #       content: Granular flow metering and control
  #       align: center
  #       background:
  #         image:
  #           filename: granularFlow.jpg
  #           filters:
  #             brightness: 0.7
  #         position: center
  #         color: '#555'
  #       link:
  #         # icon: graduation-cap
  #         # icon_pack: fas
  #         text: Read more
  #         url: 
  #     - title: Outreach
  #       content: Scientific visualization in the open house of Argonne National Laboratory
  #       align: center
  #       background:
  #         image:
  #           filename: ANL_outreach.jpg
  #           filters:
  #             brightness: 0.7
  #         position: center
  #         color: '#555'
  #       link:
  #         # icon: graduation-cap
  #         # icon_pack: fas
  #         text: Read more
  #         url: 
  #   design:
  #     # Slide height is automatic unless you force a specific height (e.g. '400px')
  #     slide_height: ''
  #     is_fullscreen: true
  #     # Automatically transition through slides?
  #     loop: false
  #     # Duration of transition between slides (in ms)
  #     interval: 2000
  - block: markdown #hero
    content:
      title: |
        The TanX Laboratory at Binghamton University
      image:
        filename: watson.jpg
      text: |

    design:
      columns: '1'
      background:
        image: 
          filename: watson.jpg
          filters:
            brightness: 0.7
          parallax: true #false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
      vertical_alignment: bottom 
  - block: markdown #hero
    content:
      title: |
        TanX Lab
      image:
        filename: watson.jpg
      text: |
      
        
        The **TanX-Lab** is a research group dedicated to advancing mechanical engineering and its applications in medicine. Our team investigates interdisciplinary problems at the interface of engineering and medicine, including drug delivery, circulating tumor cell detection, microfluidic device design, and thrombosis. We have developed an open-source large scale high performance computing framework for blood modeling considering the fluid solid interactions. 

        Our current research focuses on **physics-informed machine learning, multiscale modeling of blood flow, and inverse problems for design and optimization**.

    design:
      columns: '1'
      # background:
      #   image: 
      #     filename: watson.jpg
      #     filters:
      #       brightness: 0.7
      #     parallax: true #false
      #     position: center
      #     size: cover
      #     text_color_light: true
      # spacing:
      #   padding: ['20px', '0', '20px', '0']
      # css_class: fullscreen

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
