---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Hacks
subtitle: 'Recent and Upcoming Events'

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: hacks
  # Choose how much pages you would like to display (0 = all pages)
  count: 4
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  filters:
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: true
design:
  columns: '2'
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 2
  background:
    color: '#333'
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true
---
