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
        I’m Priscylla Silva, a Ph.D. student at the University of São Paulo (Brazil) working at the intersection of Explainable Artificial Intelligence (XAI), Visual Analytics, and Responsible AI, under the supervision of <ins>[Prof. Luis Gustavo Nonato](https://scholar.google.com/citations?user=p2tLSUsAAAAJ&hl=en)</ins>. My research focuses on developing human-centered tools that support practitioners in interpreting, comparing, and selecting feature attribution methods, enabling more transparent and trustworthy AI decision-making across domains.

        I spent one year as a visiting scholar at the <ins>[Visualization and Data Analytics Research Center (VIDA)](https://vida.engineering.nyu.edu/)</ins> at New York University (NYU), where I collaborated with <ins>[Prof. Claudio Silva](https://ctsilva.github.io/)</ins> on interactive systems for exploring disagreement among explanation methods.

        My academic path integrates AI with education, usability, and policy. During my Master’s at the Federal University of Campina Grande, I designed an Intelligent Tutoring System that provides automated feedback for programming students, under the guidance of Prof. Joseana Macêdo Fechine and <ins>[Prof. Evandro de Barros Costa](https://scholar.google.pt/citations?user=NX2ik0YAAAAJ&hl=en)</ins>. Earlier, during my undergraduate studies at the Federal University of Alagoas, I co-developed intelligent systems to teach Mathematics and Propositional Logic, which sparked my interest in using AI to support human learning and reasoning.

        Today, my research also engages with issues of AI transparency, fairness, and governance, particularly in contexts where explainability is key for accountability. I’m passionate about creating tools and knowledge that bridge technical rigor with human values—empowering experts and non-experts alike to understand, trust, and shape the AI systems that impact their lives.

        <iframe width="100%" height="284" frameborder="0" src="https://observablehq.com/embed/b8abfbb1d34a53e0@162?cells=chart"></iframe>
        
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
