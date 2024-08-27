---
title: Mary Letey
date: 2023-06-01
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hello there!
      username: admin

  - block: markdown
    id: tryagain
    content:
     title: Recent News
     subtitle:
     date_format: Jan 2006
     items:
      - date_start: '2024-05-29'
        description: ''
        organization: ''
        organization_url: 
        title: Gave a [talk](https://maryiletey.com/icl_asymptotic_kempner_24.pdf) about recent results on in context learning at Kempner Institute's ['Spring into Science' day](https://kempnerinstitute.harvard.edu/news/kempner-community-springs-into-science/). Presented posters at [DIMACS Modelling Randomness workshop](https://rmt4ai.github.io) and [Princeton ML Theory Summer School](https://mlschool.princeton.edu).
      - date_start: '2023-07-01'
        description: ''
        title: I began a summer research internship at Mila with [Prof Siamak Ravanbakhsh](https://siamak.page)
      - date_start: '2023-06-19'
        description: ''
        organization: ''
        title: I defended my master's thesis! (here's the [working-draft](https://maryiletey.com/PSIEssay2023.pdf))
    design:
      columns: '2'
      view: list
    
  - block: collection
    id: featured
    content:
      title: Publications
      count: 3
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
      # spacing:
        # padding: [0, 0, 0, 0]
    noindex: true
      
  - block: portfolio
    id: projects
    content:
      title: Projects
      count: 4
      filters:
        folders:
          - project
        exclude_featured: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # spacing:
        # padding: [0, 0, 0, 0]
    noindex: true
---
