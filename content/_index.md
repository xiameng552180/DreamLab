---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      # title: |
      #   Howdy!
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Howdy! The **Dream Lab** focuses on Human-AI Interaction, Data Visualization, and Education Technology, aiming for adaptive education with visual analytics and emerging techniques (e.g., NLP, AR/VR) to help learners discover their dreams and unlock their potential!

  - block: markdown
    content:
      title: About Us
      text: |
        Dream Lab is founded and currently directed by Meng Xia. Meng Xia is a human-computer interaction researcher and an Assistant Professor in the Department of Computer Science and Engineering at Texas A&M.

        Dream Lab focuses on building data-driven systems to help learners know how to learn and what to learn to unlock their potential; and to help educators to improve learning materials for personalized instructions. In particular, the lab explores providing adaptive education with emerging techniques in the area of Human-AI Interaction, Data Visualization, and Education Technology. These techniques include natural language processing, immersive technology (including Augmented Reality and Virtual Reality), and visual analytics. Dream Lab is dedicated to answering research questions like How to equip learners with learning analytics skills?  How to push forward learning analytics toward learning design? How to provide personalized online learning in contexts other than desktops? Beyond the Education domain, Dream Lab also studies personalization in other scenarios like personal health data analysis, investment data analysis, and so on.

        Meng’s current research focuses on designing human-centered data-driven systems for personalized online learning. She published 20+ papers at top conferences, including ACM CHI, IEEE VIS, and ACM CSCW. She received the best paper award from CHI 2022, an honorable mention award from VIS 2022, and the best poster award from VIS 2019. She serves as a program committee member for CHI, VIS, CSCW, IUI, LAK, etc. 

        Before joining Texas A&M, she worked as a postdoc at CMU under Prof. Aleven Vincent and at the Korea Advanced Institute of Science and Technology under Prof. Juho Kim. She received her Ph.D. from the Hong Kong University of Science and Technology, co-supervised by Prof. Huamin Qu and Prof. Xiaojun Ma.

  - block: markdown
    content: 
      title: Our Values
      text: |
        1. **So what?** We care about interesting and important research questions. The research questions should be interesting to you and also important to the world. Try to think about so what?
        2. **80% of success is just showing up.** We mean literally showing up. For example, showing up at the meetings, showing up at the group gatherings, etc. You can show up without solutions but only questions or even without questions. Whatever you have, you can show up and bring something back.
        3. **Fail earlier and fail faster.** Life is just a learning process, and we can gain more if we fail more. The same is true for research; it is an iterative process but not the execution of a perfect plan. 
        4. **Don't miss the deadline.** Try to experience the whole process of, for example, a paper submission period. You can learn from the feedback and be better prepared for the next try.
        5. **There is no silver bullet.** This means that there is no shortest path. 

        Last but not least, **it doesn't matter**. It doesn't matter if you "fail" this time or if you do something "stupid." And no one will spend their life only thinking about your "failure" and "stupidness." You can always do something great starting from here!
  
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