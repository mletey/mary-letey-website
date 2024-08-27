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
    
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: post
      count: 5
      offset: 0
      order: desc
      filters:
        folders:
          - news
    design:
      columns: '2'
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
    
  - block: collection
    id: featured
    content:
      title: Publications
      count: 3
      offset: 0
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
    noindex: true
      
  - block: portfolio
    id: projects
    content:
      title: Projects
      count: 4
      offset: 0
      filters:
        folders:
          - project
        exclude_featured: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
    noindex: true
---
