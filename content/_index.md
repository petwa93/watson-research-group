---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Watson Laser Lab
      image:
        filename: B500.jpg
      text: |
        <br>
        
        The **Watson Laser Lab** is a broad physical chemistry research group at Curtin University with specialisations in gas-phase spectroscopy.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 3
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
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: LuJ_machine.jpg
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
      title: Latest Published Work
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_types:
          - 'article-journal'
          - 'article'
          - 'book'
          - 'chapter'
#        date:
#          - start: '2024-01-01'
#            end: ''
        recursive: true
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./team/people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
