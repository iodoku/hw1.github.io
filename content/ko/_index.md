---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
      
  - block: features
    content:
      title: <span style="font-size:75%; color:orange;">게임을 통해 즐거움을 창조하고 싶은 개발자입니다! </span>
      text: <span style="font-size:110%">안녕하세요! 전북대학교 컴퓨터공학부 장동하입니다. <br>게임 개발에 열정을 가지고 있으며, Unity를 활용한 프로젝트 경험이 있습니다.</span>


  - block: slider
    content:
      slides:
      - title: AI
        content: 'Just opened last month!'
        align: center
        background:
          image:
              caption: 'Image credit: [**Unsplash**](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EB%B9%A8%EA%B0%84-%ED%85%8C%EC%9D%B4%EB%B8%94%EC%97%90-%EB%91%90-%EA%B0%9C%EC%9D%98-%EB%AF%B8%EB%8B%88%EC%96%B8%EC%A6%88-%EC%BA%90%EB%A6%AD%ED%84%B0-%ED%94%BC%EA%B7%9C%EC%96%B4-tloFnD-7EpI)'
              focal_point: ""
              preview_only: false
          position: center
          color: '#333'
      - title: Medical AI
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000  


  - block: collection
    content:
      title: Portfolio
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      page_type: portfolio
    design:
      view: community/customblue
      columns: '1'
    
  - block: collection
    content:
      title: Practices
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      page_type: practices
    design:
      view: community/customgreen
      columns: '1'
  
  - block: collection
    content:
      title: Ideas
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      page_type: ideas
    design:
      view: community/custompurple
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

  - block: collection
    content:
      title: Latest Preprints
      text: ""
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
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
