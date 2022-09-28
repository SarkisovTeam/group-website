---
widget: slider
weight: 10
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: True
  # Duration of transition between slides (in ms)
  interval: 6000

content:
  slides:
    - title: Welcome to our group
      content: Overview of the research themes
      align: center
      background:
        position: center
        size: cover
        color: '#666'
        brightness: 0.35
        media: 8.png
        fit: contain
    - title: 🛠️ Multiscale Workflows for Materials Screening
      content: 'Computational characterization, molecular simulations and process modelling'
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.35 
        media: matopt3.png
        fit: contain
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Go to Projects
        url: ../project/        
    - title: Material Informatics 🧮   
      content: 'Deeper understanding of nanoporous materials'
      align: center
      background:
        position: center
        image_color: '#555'
        brightness: 0.35
        media: 4.png
        fit: contain
      link:
        icon: graduation-cap
        icon_pack: fas  
        text: Go to Projects
        url: ../project/
    - title: Energy Efficient Separations ⛽  🧪
      content: 'Achieving difficult separations via adsorption'
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.25
        media: 1.png 
        fit: contain
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Go to Projects
        url: ../project/
    - title: Models and Software 💻
      content: 'Efficient algorithms with open-source distribution'
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.35
        media: 12.png
        fit: contain
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Go to projects
        url: ../project/
---
