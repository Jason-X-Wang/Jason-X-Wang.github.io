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
      animation:
        name: fadeInUp

  # --- HIGH-VISIBILITY FEATURED NEWS SECTION ---
  - block: collection
    id: news
    content:
      # Sheffield Blue background (#003057) with Gold border highlight
      title: '<span style="background-color: #003057; color: white; padding: 6px 15px; border-radius: 4px; border-left: 6px solid #ffcc00; font-weight: bold; font-family: sans
