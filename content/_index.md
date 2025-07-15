---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-07-15
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
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
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        My research centers on **customer engagement**, **online brand communities (OBCs)**, and **sustainable digital consumer behavior**.

        I apply a blend of **qualitative** (e.g., phenomenological interviews, Delphi technique) and **quantitative** (e.g., surveys, SEM, experimental design) methods to explore how psychological and contextual factors influence brand-consumer relationships in digital environments.

        One of my recent works explores how self-transcendent emotions influence consumers' sustainable actions in tourism through **digital storytelling** — [read here](/publication/roopak-eco-stories-2025/).  
        
        My paper on **framing effects in customer engagement research** offers a systematic review and identifies new conceptual pathways — [view publication](/publication/roopak-framing-2024/).

        I also study **psychological antecedents** like the need for validation and social connection in OBCs. You can explore those findings in [this journal article](/publication/roopak-engaged-2025/).

        I am currently building a game-theoretic research stream on **digital consent transparency**, and welcome collaborations at this intersection of behavioral marketing, strategy, and public policy.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      view: article-grid
#      columns: 1

#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: post
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: date-title-summary
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
---