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
      username: roopendra-roopak
      text: ""
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
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
  - block: resume-languages
    content:
      title: Languages
      username: roopendra-roopak
    design:
      columns: 2
      chart: true 
  - block: resume-skills
    content:
      title: Skills & Hobbies
      # Note: `username` refers to the user's folder name in `content/authors/`
      username: roopendra-roopak
    design:
      columns: 2
      chart: true 
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        My research primarily revolves around [**customer engagement**](/publication/roopak-framing-2024/), with a particular focus on its psychological and contextual underpinnings in digital environments.
        
        I have investigated **psychological antecedents** such as the [**need for validation**](/publication/roopak-engaged-2025/), social needs, and status needs to understand what motivates consumers to engage in [**online brand communities (OBCs)**](/publication/roopak-engaged-2025/). Drawing on frameworks such as **Self-Determination Theory** and **Social Exchange Theory**. This research explores how intrinsic motivations shape participation in online brand communities.
        
        To advance conceptual clarity, I conducted a [**systematic and multimethod review**](/publication/roopak-framing-2024/) of customer engagement research. This study identifies evolving **framing strategies**, theoretical gaps, and future research trajectories across marketing and consumer behavior domains.
        
        In applied work, I examine how [**digital storytelling**](/publication/roopak-eco-stories-2025/) can foster engagement with sustainability-focused brands. My recent case study on *Rustic Hue®* illustrates how ethical fashion brands use storytelling to build **cultural relevance**, enhance consumer trust, and communicate environmental practices such as upcycling and zero-waste production.
        
        Currently, I am expanding this line of inquiry to explore **sustainable consumer behavior** through the lens of **engagement**, examining how psychological drivers continue to shape pro-social and eco-conscious interactions in digital and experiential contexts.
        
        In parallel, I am developing a theoretical stream using [**game theory**](/) to model platform strategies around [**digital consent transparency**](/), and examine its implications for user utility, firm incentives, and public policy.
    design:
      columns: '1'
# - block: collection
#   id: papers
#   content:
#     title: Featured Publications
#     filters:
#       folders:
#         - publication
#       featured_only: true
#   design:
#     view: article-grid
#     columns: 2
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: contact
    id: contact
    content:
      title: "Connect with Me"
      text: |
        I am always happy to talk about research, collaboration, or anything marketing-related.  
        Feel free to reach out or follow me on these platforms:
    contacts:
      - icon: at-symbol
        name: Email
        link: mailto:rupendra.r@gmail.com

      - icon: google-scholar
        name: Google Scholar
        link: https://scholar.google.com/citations?user=stFFZ5oAAAAJ

      - icon: orcid
        name: ORCID
        link: https://orcid.org/0000-0001-7122-2434

      - icon: researchgate
        name: ResearchGate
        link: https://www.researchgate.net/profile/Roopendra-Roopak

      - icon: linkedin
        name: LinkedIn
        link: https://www.linkedin.com/in/roopendra-roopak/

      - icon: github
        name: GitHub
        link: https://github.com/roopendra-roopak
    design:
      columns: 2
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