---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: JangDongha
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
            <span style="font-size:90%; text-align: justify;">I have a solid understanding of object-oriented programming.</span><br><br>

        - name: Unity
          icon: unity
          icon_pack: fab
          description: |
            <span style="font-size:90%; text-align: justify;">I develop various 2D and 3D game projects using Unity.</span><br><br>

        - name: Art
          icon: bilibili
          icon_pack: fab
          description: |
            <span style="font-size:90%; text-align: justify;">I create character designs and graphics using Aseprite and Photoshop.</span><br><br>

        - name: Level
          icon: laravel
          icon_pack: fab
          description: |
            <span style="font-size:90%; text-align: justify;">I am a developer who constantly strives to improve and grow.</span><br><br>

        - name: Creative
          icon: reacteurope
          icon_pack: fab
          description: |
            <span style="font-size:90%; text-align: justify;">I design fun gameplay experiences by planning game concepts, stories, and mechanics.</span><br><br>

        - name: Game 
          icon: gamepad
          icon_pack: fas
          description: |
            <span style="font-size:90%; text-align: justify;">I enjoy playing various genres of games and building my experience.</span><br><br><br><br>

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
        content: 'I want to be a developer who makes games with a smile!'
        align: center
        background:
          image:
            filename: minions.jpg
            filters:
              brightness: 0.7
          position: top
          color: '#333'
      - title: Like
        content: 'I want to spend my life doing what I love!'
        align: center
        background:
          image:
            filename: pixel.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
      - title: Dream
        content: 'I want to keep working tirelessly toward my dreams!'
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
