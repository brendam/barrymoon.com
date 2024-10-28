---
title: 'Home'
date: "2024-10-28"
type: landing

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      spacing:
        padding: [0, 0, 0, 0]
      biography:
        style: 'text-align: justify; font-size: 0.8em;'

  - block: collection
    content:
      filters:
        folders:
          - post
      count: 25
    design:
      view: article-grid
---
