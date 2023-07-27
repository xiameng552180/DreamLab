---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        ## Howdy!
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Dream Lab** focuses on Human-AI Interaction, Data Visualization, and Education Technology, aiming for adaptive education with visual analytics and emerging techniques (e.g., NLP, AR/VR) to help learners discover their dreams and unlock their potential!

  - block: markdown
    content: 
       title: |
        ## Latest News
      text: |
        1. **So what?** We care about interesting and important research questions. The research questions should be interesting to you and also important to the world. And try to think about so what?
        2. **80% of success is just showing up.** We mean literally showing up. For example, showing up at the meetings, showing up at the group gatherings, etc. You can show up without solutions but only questions or even without questions. Whatever you have, you can show up and bring something back.
        3. **Fail earlier and fail faster.** Life is just a learning process, and we can gain more if we fail more. The same is true for research; it is an iterative process but not the execution of a perfect plan. 
        4. **Don't miss the deadline.** Try to experience the whole process of, for example, a paper submission period. You can learn from the feedback and be better prepared for the next try.
        5. **There is no silver bullet.** This means that there is no shortest path. 

        Last but not least, **it doesn't matter**. It doesn't matter if you "fail" this time or if you do something "stupid." And no one will spend their life only thinking about your "failure" and "stupidness." You can always do something great starting from here!
  
  - block: collection
    content:
      title: |
        ## Latest News
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