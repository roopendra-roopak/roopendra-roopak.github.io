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
        My research primarily revolves around **customer engagement**, with a particular focus on its psychological and contextual underpinnings in digital environments.
        
        I have examined **psychological antecedents** such as the **need for validation**, **social needs**, and **status needs** to understand what motivates consumers to participate in and contribute to **online brand communities (OBCs)**. Drawing on **Self-Determination Theory** and **Social Exchange Theory**, this work uncovers how intrinsic motivations drive sustained engagement behaviors in online brand communities ([journal article](/publication/roopak-engaged-2025/)).
        
        To deepen conceptual clarity in the field, I conducted a **systematic and multimethod review** of customer engagement research. This study maps the evolving **framing strategies**, highlights key theoretical gaps, and identifies future research pathways to advance engagement scholarship across disciplines ([publication](/publication/roopak-framing-2024/)).
        
        Building on these foundations, I have explored **digital storytelling** as a strategic tool for fostering engagement with **sustainability-oriented brands**. In a recent case study of [Rustic Hue®](/publication/roopak-eco-stories-2025/), I demonstrate how ethically rooted fashion brands leverage storytelling to build **cultural relevance**, **consumer trust**, and promote **environmental awareness** through narratives that center around upcycling, community collaborations, and heritage preservation.
        
        Currently, I am extending my work on engagement to the context of **sustainable consumer behavior** in tourism, particularly how **self-transcendent emotions** such as awe and compassion influence visitors' pro-environmental actions and **ESG engagement** with local communities and destinations.
        
        In parallel, I am developing a **game-theoretic research stream** to model how **transparency in digital consent** affects platform strategy, user utility, and broader questions of consumer welfare and public policy—marking a methodological expansion into **behavioral strategy** and **digital ethics**.
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