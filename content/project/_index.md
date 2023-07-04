---
title: Projects
# date: 2023-07-12
type: landing

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citations
view: 2

# Optional header image (relative to `static/media/` folder).
header:
  caption: ''
  image: ''

sections:
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      sort_by: Weight
      sort_ascending: true
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      tags: []
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: PDF
          tag: PDF
        - name: Sewing 
          tag: Sewing
        - name: Open Source
          tag: FOSS
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
---