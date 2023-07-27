---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Howdy!
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Dream Lab** mainly focuses on Human-AI Interaction, Data Visualization, and Education Technology. We aim to achieve adaptive learning/teaching with visual analytics, other emerging techniques (e.g., NLP, AR/VR), and intelligent tutoring systems authoring tools.

  - block: markdown
    content: 
      title: Our Values
      text: |
        1. Choose interesting and import research tipics and aswer so what?
        2. %80 of success is just show up.
        3. Fail earlier and fail faster.
        4. Don't miss deadline.
        5. There is no silver bullet.
  
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
      view: card
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---