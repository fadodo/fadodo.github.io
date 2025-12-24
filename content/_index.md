---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-07-18
type: landing

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: hero
    content:
      title:'Use Earth observation data as a tool to inform decision-making'
      text: |-
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "min-height: 0; height: auto;"
      view: 1 # 1 is usually the smallest/automatic setting
      background:
        color: black
        text_color_light: true
        image:
          # Reference an image in your `assets/media/` stacked-peaks.svg folder choked_peoples.jpg
          filename: hurricane.jpg
          filters:
            brightness: 1.0
  # ------------------------------------------------------------------
  # ⭐ NOUVEAU BLOC "MES SERVICES" ⭐
  # ------------------------------------------------------------------
  - block: features
    id: services
    content:
      title: Services
      subtitle: |
        I put my technical expertise and strategic vision at the service of your projects.
      items:
        - name: Project Management
          description: Coordination and management of scientific and technical projects to ensure their success.
          icon: briefcase
        - name: Scientific Communication
          description: Communication activities to make science accessible and understandable.
          icon: megaphone
        - name: Technical Writing
          description: Technical writing and the valorization of scientific results and solutions.
          icon: clipboard-document-list
        - name: Training and Awareness
          description: Training and awareness sessions on data science and analysis tools.
          icon: academic-cap
        - name: Research and Development
          description: R&D of tools and solutions to support decision-making.
          icon: beaker
        - name: Prediction Platform
          description: Proposal for an early warning and prediction platform for coastal overflow risks in West Africa.
          icon: bell-alert
    design:
      columns: 3
  # ------------------------------------------------------------------
  # ⭐ BLOC "ABOUT ME"⭐
  # ------------------------------------------------------------------
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.Shocked_peoples.jpg , stacked-peaks.svg
          filename: ''
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: true
          text_color_light: true
  # ------------------------------------------------------------------
  # ⭐ BLOC "MES PROJETS" ⭐
  # ------------------------------------------------------------------
  - block: collection
    id: projects
    content:
      title: Projects
      subtitle: ''
      text: 'Check out my projects below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # Folders to display content from
        folders:
          - project
        author: ''
        category: ''
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
      columns: 3
  # ------------------------------------------------------------------
  # ⭐ BLOC "MES COMPETENCES"  ⭐
  # ------------------------------------------------------------------
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
          icon: globe-europe-africa
        - name: Time-series analysis
          description: ''
          #percent: 80
          icon: presentation-chart-bar 
        - name: Data Analytics
          description: ''
          #percent: 100
          icon: chart-pie
        - name: SQL
          description: ''
          #percent: 40
          icon: table-cells
        - name: Machine Learning
          description: ''
          #percent: 80
          icon: computer-desktop
    design:
      css_class: dark
      background:
        color: black
  # ------------------------------------------------------------------
  # ⭐ BLOC "PUBLICATIONS" ⭐
  # ------------------------------------------------------------------
  - block: collection
    id: papers
    content:
      title: Publications
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
  # ------------------------------------------------------------------
  # ⭐ BLOC "VULGARISATION ET PRESENTATION"  ⭐
  # ------------------------------------------------------------------
  - block: collection
    id: talks
    content:
      title: Outreach & Talks
      text: ''
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 2
  # ------------------------------------------------------------------
  # ⭐ BLOC "EVENEMENTS"  ⭐
  # ------------------------------------------------------------------
  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: 'COMING SOON ....'
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
