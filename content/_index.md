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
      title: Use Earth observation data as a tool to inform decision-making
      text: |-
        **Flood Rapid Mapping Tools** 
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: ""
      background:
        color: black
        text_color_light: true
        image:
          # Reference an image in your `assets/media/` stacked-peaks.svg folder choked_peoples.jpg
          filename: hurricane.jpg
          filters:
            brightness: 1.0
  # ------------------------------------------------------------------
  # ⭐ NOUVEAU BLOC "MES SERVICES" INSÉRÉ ICI (avant resume-biography-3) ⭐
  # ------------------------------------------------------------------
  - block: features
    content:
      title: Mes Services
      subtitle: |
        Je mets mon expertise technique et ma vision stratégique au service de vos projets.
      items:
        - name: Gestion de Projet
          description: Coordination et gestion de projets scientifiques et techniques pour assurer leur succès.
          icon: cogs

        - name: Communication Scientifique
          description: Activités de communication pour rendre la science accessible et compréhensible.
          icon: bullhorn

        - name: Rédaction Technique
          description: Rédaction technique et valorisation des résultats et solutions scientifiques.
          icon: file-alt

        - name: Formation et Sensibilisation
          description: Formation et sensibilisation à la science de la donnée et aux outils d'analyse.
          icon: chart-line

        - name: Recherche et Développement
          description: R&D d'outils et solutions pour l'aide à la prise de décision.
          icon: microchip

        - name: Plateforme de Prédiction
          description: Proposition d'une plateforme de prédiction et d'alerte précoce pour les risques de surcotes en Afrique de l'Ouest.
          icon: cloud-sun-rain

    design:
      columns: 3
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
    design:
      css_class: dark
      background:
        color: black
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
