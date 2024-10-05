---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing


sections:

  - block: about.biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: 장동하
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false


  - block: features
    content:
      text: |
        {{% cta cta_link="https://drive.google.com/uc?export=download&id=1RJ9F3HT7VIPxVaRyXJSp3Xytb7jcdWW5" cta_text="Download Introduce PDF" %}}
      
      items:
        - name: C#
          icon: c
          icon_pack: fas
          description: |
            <span style="font-size:90%; text-align: justify;">객체 지향 프로그래밍에 대한 이해를 가지고 있습니다.</span><br><br>

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
          description:  <span style="font-size:90%">다양한 장르의 게임을 즐기며 경험을 쌓고 있습니다.</span><br><br><br><br>


      

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
      background:
        color: '#C5D1B4'
    
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
      background:
        color: '#F5E7C1'
  
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
      background:
        color: '#C5D1B4'

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
---
