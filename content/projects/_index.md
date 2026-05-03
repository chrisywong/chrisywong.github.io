---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  # - block: collection
  #   content:
  #     title: Selected Projects
  #     text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
  #     filters:
  #       folders:
  #         - projects
  #   design:
  #     view: article-grid
  #     fill_image: false
  #     columns: 3
  #     show_date: false
  #     show_read_time: false
  #     show_read_more: false
  - block: portfolio
    id: projects
    content:
      title: Research Projects
      filters:
        folders:
          - projects
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Active Projects
          tag: 'active'
        - name: Past Projects
          tag: old
---
