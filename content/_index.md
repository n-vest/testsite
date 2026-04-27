---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-01-01
type: landing

sections:
  - block: about.biography
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      buttons:
        - name: All
          tag: '*'
        - name: Integers
          tag: Integers
        - name: Patterns
          tag: Patterns
        - name: Algebra
          tag: Algebra
    design:
      # 2x2 grid layout — see assets/scss/custom.scss for hairline-divider styling.
      columns: '2'
      view: grid
      flip_alt_rows: false
---
