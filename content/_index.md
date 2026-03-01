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
        Jason is a Lecturer of Sustainable Supply Chain Management at Sheffield University Management School. Previously, he worked at University of Huddersfield as MBA programme leader and Senior Lecturer of Operations and Supply Chain Management.
        
        Focusing on sustainable/circular supply chain management applied with carbon neutrality and blockchain, Jason's work has been published in leading international journals, including the International Journal of Operations and Production Management, Transportation Research Part E: Logistics and Transportation Review, and International Journal of Production Economics.
        
        Jason is the Editorial Review Board member of Journal of Supply Chain Management and IEEE Transactions on Engineering Management, Guest Editor of Transportation Research Part E: Logistics and Transportation Review, and Senior Editor (Operations Research, Information & Technology) in Cogent Business & Management.
        
        His work attracted attention from the industrial community, providing consultation to vehicle recovery service supply chain in New Zealand and the motorsport industry in UK.
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
