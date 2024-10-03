---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: features
    id: features
    content:
      title: <span style="font-size:75%; color:orange;">게임을 통해 즐거움을 창조하고 싶은 개발자입니다! </span><br><br>
      text: <span style="font-size:110%">안녕하세요! 전북대학교 컴퓨터공학부 장동하입니다. <br>게임 개발에 열정을 가지고 있으며, Unity를 활용한 프로젝트 경험이 있습니다.</span><br><br><br><br>

      items:
        - name: C#
          icon: c
          icon_pack: fas
          description: <span style="font-size:90%">객체 지향 프로그래밍에 대한 이해를 가지고 있습니다.</span><br><br>

        - name: Unity
          icon: unity
          icon_pack: fab
          description:  <span style="font-size:90%">Unity를 사용하여 다양한 2D 및 3D 게임 프로젝트를 개발하고 있습니다.</span><br><br>

        - name: Art
          icon: bilibili
          icon_pack: fab
          description:  <span style="font-size:90%">Aseprite와 Photoshop을 활용하여 캐릭터 디자인 및 그래픽을 제작합니다.</span><br><br>

        - name: Level
          icon: laravel
          icon_pack: fab
          description:  <span style="font-size:90%">계속해서 노력하며 성장하는 개발자입니다.</span><br><br>

        - name: Creative
          icon: reacteurope
          icon_pack: fab
          description:  <span style="font-size:90%">게임 컨셉과 스토리, 메커니즘을 기획하며 재미있는 플레이 경험을 설계합니다.</span><br><br>

        - name: Game 
          icon: gamepad
          icon_pack: fas
          description:  <span style="font-size:90%">다양한 장르의 게임을 즐기며 경험을 쌓고 있습니다.</span><br><br>

  - block: skills
      name: Technical Skills
      items:
        - name: C#
          description: "Unity 개발의 주 프로그래밍 언어."
          percent: 80
          icon: c
          icon_pack: fas
        - name: Unity
          description: "2D 및 3D 게임 프로젝트 개발 경험."
          percent: 85
          icon: unity
          icon_pack: fab
        - name: Python
          description: "데이터 분석 및 간단한 자동화 스크립트 작성."
          percent: 70
          icon: python
          icon_pack: fab

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

  - block: slider
    content:
      slides:
      - title: Fun
        content: '웃으며 게임을 제작하는 개발자가 되고 싶습니다!'
        align: center
        background:
          image:
            filename: minions.jpg
            filters:
              brightness: 0.7
          position: top
          color: '#333'
      - title: Like
        content: '좋아하는 일을 하며 인생을 보내고 싶습니다!'
        align: center
        background:
          image:
            filename: pixel.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: Dream
        content: '끊임없이 꿈을 위해 노력하고 싶습니다!'
        align: center
        background:
          image:
            filename: disney.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
    design:
      slide_height: '400px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000  

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
