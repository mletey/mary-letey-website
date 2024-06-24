---
title: Mary Letey
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Hello There!
      username: admin
    noindex: true

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
    noindex: true
---
