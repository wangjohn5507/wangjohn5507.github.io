---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "2rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:

  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/Chung-Yu Wang-Resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: 
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'

  - block: experience
    id: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: align

  - block: collection
    id: projects
    content:
      title: Featured Projects
      subtitle: ''
      text: 'Check out my featured projects below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: card

  # - block: awards
  #   content:
  #     title: Awards
  #     username: admin

  - block: languages
    content:
      title: Languages
      username: admin
---
