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



  - block: collection
    content:
      title: Projects
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      page_type: projects
    design:
      view: community/customradius
      columns: '1'
    
  - block: collection
    content:
      title: Practies
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      page_type: practices
    design:
      view: community/customrotation
      columns: '1'
  
  - block: collection
    content:
      title: Planning(기획중)
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      page_type: planning
    design:
      view: community/customradius
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
