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
    - title: 👋 Welcome to the group
      content: Here's an overview of our research in adsorption...
      align: center
      background:
        position: center
        size: cover
        color: '#666'
        brightness: 0.7
        media: irmof_field.png
        fit: fill
        image_size: contain
    - title: Material Informatics 🧮   
      content: 'Deeper understanding of nanoporous materials'
      align: center
      background:
        position: center
        image_color: '#555'
        brightness: 0.7
        media: mat_char_image.png
        fit: stretch  
        image_size: contain
      link:
        icon: graduation-cap
        icon_pack: fas  
        text: Go to Projects
        url: ../project/matchar
    - title: Energy Efficient Separations ⛽  🧪
      content: 'Achieving difficult separations via adsorption'
      align: center
      background:
        position: center
        fit: stretch  
        image_size: contain
        color: '#333'
        brightness: 0.5
        media: 2.png

      link:
        icon: graduation-cap
        icon_pack: fas
        text: Go to Projects
        url: ../project/matsep
    - title: Models and Software 💻
      content: 'Efficient algorithms with open-source distribution'
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: 12.png
        fit: stretch  
        image_size: contain
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Go to Projects
        url: ../project/
    - title: 🛠️Materials in High-throughput
      content: 'Learning, screening and optimizing in large numbers'
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.9
        media: matopt_7.png
        fit: contain 
        image_size: contain
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Go to Projects
        url: ../project/        
---
