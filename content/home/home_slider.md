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
      content: Here's an overview of our research...
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.7
        media: irmof_field.png
        fit: fill
    - title: Material Informatics 🧮   
      content: 'Deeper understanding of  nanoporous materials'
      align: right
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: mat_char_image2.png
      link:
        icon: graduation-cap
        icon_pack: fas  
        text: Read more
        url: ../project/matchar
    - title: Energy Efficient Separations ⛽  🧪
      content: 'Achieving difficult separations via adsorption'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: 2.png
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Read more
        url: ../project/matsep
    - title: Models and Software 💻
      content: 'Efficient algorithms with open-source distribution'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: 12.png
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Read more
        url: ../project/DMFT
    - title: Materials Optimization 🛠️
      content: 'Fine-tuning nanoporous materials for specific applications'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.9
        media: matopt4_1.png
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Read more
        url: ../project/matgen
---
