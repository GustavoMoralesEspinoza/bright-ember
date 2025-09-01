---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        CebrianLab  
        Smart Grids & Power Systems
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **CebrianLab** is dedicated to advancing research in **smart grids, distribution network planning, renewable energy integration, hosting capacity, and optimization algorithms**.  
        Based at the University of São Paulo (USP), our mission is to combine **theory, simulation, and real-world applications** to support the energy transition.

  - block: collection
    content:
      title: Latest News
      subtitle:
      text: Stay up to date with our activities, projects, and conference participation.
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
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        **Our Vision**  
        At CebrianLab, we aim to address the challenges of modern distribution systems through innovation, collaboration, and academic excellence.  
        Our research spans from **Monte Carlo simulations** to **AI-driven optimization**, applied to real Brazilian distribution networks.
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

  - block: collection
    content:
      title: Latest Publications
      text: Explore our recent work presented at international conferences and published in leading journals.
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the CebrianLab Team →" %}}
    design:
      columns: '1'
---
