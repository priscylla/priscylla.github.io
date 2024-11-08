---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: prospect_park.jpg
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
  #- block: stats
  #  content:
  #    items:
  #      - statistic: "15"
  #        description: |
  #          Publications
  #      - statistic: "1,000+"
  #        description: |
  #          Citations
  #      - statistic: "78"
  #        description: |
  #          h-index
  #  design:
  #    # Section background color (CSS class)
  #    css_class: "bg-gray-100 dark:bg-gray-900"
  #    # Reduce spacing
  #    spacing:
  #      padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: 'Hello 👋'
      subtitle: ''
      text: |-
        I’m Priscylla Silva, a Ph.D. student in Explainable Artificial Intelligence (XAI) at the University of São Paulo (Brazil), advised by <ins>[Prof. Luis Gustavo Nonato](https://scholar.google.com/citations?user=p2tLSUsAAAAJ&hl=en)</ins>. My research focuses on developing tools and techniques that improve AI interpretability, allowing for more transparent and reliable decision-making in a variety of domains.

        I spent a year as a visiting scholar at the <ins>[Visualization and Data Analytics Research Center (VIDA)](https://vida.engineering.nyu.edu/)</ins> at New York University (NYU), where I worked under the guidance of <ins>[Prof. Claudio Silva](https://ctsilva.github.io/)</ins>.

        My research journey began with a strong foundation in Artificial Intelligence in Education during my Master’s degree at the Federal University of Campina Grande (Brazil). Under the mentorship of Prof. Joseana Macêdo Fechine and Prof. Evandro de Barros Costa, I developed an Intelligent Tutoring System with automatic feedback designed to support students in introductory computer science (CS1) courses.

        In my undergraduate studies at the Federal University of Alagoas (Brazil), I collaborated as a developer on two intelligent tutoring systems focused on Mathematics and Propositional Logic. These experiences cultivated my passion for creating AI systems that not only process data but also actively contribute to human learning and understanding.
    design:
      columns: '1'
  #- block: collection
  #  content:
  #    title: Recent News
  #    subtitle: ''
  #    text: ''
  #    # Page type to display. E.g. post, talk, publication...
  #    page_type: post
  #    # Choose how many pages you would like to display (0 = all pages)
  #    count: 5
  #    # Filter on criteria
  #    filters:
  #      author: ""
  #      category: ""
  #      tag: ""
  #      exclude_featured: false
  #      exclude_future: false
  #      exclude_past: false
  #      publication_type: ""
  #    # Choose how many pages you would like to offset by
  #    offset: 0
  #    # Page order: descending (desc) or ascending (asc) date.
  #    order: desc
  #  design:
  #    # Choose a layout view
  #    view: date-title-summary
  #    # Reduce spacing
  #    spacing:
  #      padding: [0, 0, 0, 0]
---
