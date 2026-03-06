---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Eliminate the global default spacing entirely
  spacing: '0'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        Research interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
      # Force minimal padding at the very top block
      spacing:
        padding: [0, 0, '1rem', 0]

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
      spacing:
        padding: ['1rem', 0, '1rem', 0]

  - block: collection
    id: papers
    content:
      title: Peer-Reviewed Publications
      filters:
        folders:
          - publications
        # This ensures ONLY journal articles show up here
        publication_type: 'article-journal'
      count: 0
    design:
      view: citation
      spacing:
        padding: ['1rem', 0, '1rem', 0]

  - block: collection
    id: working-papers
    content:
      title: Working Papers
      filters:
        folders:
          - publications
        # Grabs only the papers tagged as manuscripts
        publication_type: 'manuscript'
      count: 0
    design:
      view: citation
      spacing:
        padding: ['1rem', 0, '1rem', 0]

     - block: collection
    id: book-chapters
    content:
      title: Book Chapters
      filters:
        folders:
          - publications
        # This creates the dedicated Book Chapters section
        publication_type: 'chapter'
      count: 0
    design:
      view: citation
      spacing:
        padding: ['1rem', 0, '1rem', 0]

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
      spacing:
        padding: ['1rem', 0, '1rem', 0]

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
        padding: ['1rem', 0, 0, 0]
---
