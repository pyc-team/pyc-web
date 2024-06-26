---
title: People
date: 2022-10-24

type: landing

sections:
  # A section to display people
  - block: collection
    id: team
    content:
      title: The Core PyC Team
      subtitle: Meet the people behind PyC
#      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      # Display content from the `content/post/` folder
      filters:
        folders:
          - authors
    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: cards
#      # For the Showcase view, do you want to flip alternate rows?
#      flip_alt_rows: true
---