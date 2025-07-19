---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-07-18
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Use Earth observation data as a tool to inform decision-making
      # Add your Hero text here
      text: |-
        **Flood Rapid Mapping Tools** 
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      # Choose an optional background color, gradient, image, or video
      background:
        color:""
        text_color_light: true
        image:
          # Reference an image in your `assets/media/` stacked-peaks.svg folder choked_peoples.jpg
          filename:hurricane.jpg
          filters:
            brightness:0.5
  - block: stats
    content:
      items:
        - statistic: "2 stars"
          description: |
            GitHub stars  
            since 2025
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-800"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: black
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.stacked-peaks.svg
          filename: shocked_peoples.jpg
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque
            brightness: 1.0
          # Image fit. Options are `cover` (default), `contain`, or `actual` size
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: false
  - block: collection
    id: projects
    content:
      title: Projects
      subtitle: My subtitle
      text: 'Check out my projects below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # Folders to display content from
        folders:
          - project
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
      view: article-grid
  - block: features
    content:
      title: Skills
      subtitle: ''
      text: ''
      items:
        - name: Python programming
          description: ''
          #percent: 80
          icon: python
        - name: Earth Observation
          description: ''
          #percent: 80
          icon: globe-alt
        - name: Time-series analysis
          description: ''
          #percent: 80
          icon: chart-bar 
        - name: Data Analytics
          description: ''
          #percent: 100
          icon: document-chart-bar
        - name: SQL
          description: ''
          #percent: 40
          icon: circle-stack
        - name: Machine Learning
          description: ''
          #percent: 80
          icon: cpu-chip
  - block: collection
    id: papers
    content:
      title: Main Publications
      filters:
        folders:
          - publication
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
      view: citation
      columns: 2
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Outreach
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: 'COMING SOON !!!'
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
