---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: markdown
    content:
      title: '📚 My Research & Background'
      subtitle: ''
      text: |-
        Jason’s core research focuses on two broad themes:

        1. **Sustainable/circular supply chain management**, with a particular focus on customer-driven supply chain sustainability practices and their impacts on supplying firms. This includes using carbon neutrality practices, circular product design, business model innovation, and supply chain redesign to improve economic and environmental benefits in sustainable development.
        2. **The application of blockchain technology** in supply chain management, exploring its contributions to supply chain transparency, visibility, and traceability, and thus the development of supply chain resilience and robustness.

        Jason also works on manufacturing and sustainability innovation in the construction sector, such as prefabricated construction, to develop sector-specific sustainability strategies.
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
      # Setting count to 0 displays all papers without a cutoff limit
      count: 0
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
