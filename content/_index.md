---
# Leave the homepage title empty to use the site title
title: ""
summary: ""
date: 2022-10-24
type: landing

design:
  spacing: "0"

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ""
        education: ""
        Research interests: ""
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
      spacing:
        padding: [0, 0, "1rem", 0]

  - block: markdown
    content:
      title: "📚 My Research & Background"
      subtitle: ""
      text: |-
        Jason’s core research focuses on two broad themes:

        1. **Sustainable/circular supply chain management**, with a particular focus on customer-driven supply chain sustainability practices and their impacts on supplying firms. This includes using carbon neutrality practices, circular product design, business model innovation, and supply chain redesign to improve economic and environmental benefits in sustainable development.
        2. **The application of blockchain technology** in supply chain management, exploring its contributions to supply chain transparency, visibility, and traceability, and thus the development of supply chain resilience and robustness.

        Jason also works on manufacturing and sustainability innovation in the construction sector, such as prefabricated construction, to develop sector-specific sustainability strategies.
    design:
      columns: "1"
      spacing:
        padding: ["1rem", 0, "1rem", 0]
      animation:
        name: fadeInUp

  - block: collection
    id: news
    content:
      title: '<span style="background-color:#003057;color:white;padding:6px 12px;border-radius:4px;border-left:6px solid #ffcc00;">🔥 LATEST UPDATES & NEWS</span>'
      subtitle: "Recent announcements and academic activities"
      page_type: blog
      count: 2
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
    design:
      view: showcase
      columns: "1"
      spacing:
        padding: ["2.5rem", 0, "2.5rem", 0]
      animation:
        name: bounceIn

  - block: markdown
    content:
      title: "🤝 Professional Services"
      subtitle: ""
      text: |-
        **Editorial Board**
        * Department Editor (Operations Research, Information and Technology) [Cogent Business & Management](https://www.tandfonline.com/action/journalInformation?show=editorialBoard&journalCode=oabm20) (JIF: 3.0, ABS: 1, Taylor & Francis), 2022-present
        * Editorial Review Board Member, [Journal of Supply Chain Management](https://onlinelibrary.wiley.com/page/journal/1745493x/homepage/editorialboard.html) (JIF: 10.6, ABS: 4, ABDC: A, Wiley), 2021-present
        * Editorial Review Board Member, [IEEE Transactions on Engineering Management](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10356850) (JIF: 5.2, ABS: 3, ABDC: A, IEEE Xplore), 2025-present

        **Special Issue Guest Editor**
        * “[Logistics and Supply Chain Management with Web 3.0 and Metaverse Technologies](https://www.sciencedirect.com/journal/transportation-research-part-e-logistics-and-transportation-review/about/call-for-papers),” Transportation Research Part E: Logistics and Transportation Review (JIF: 8.8, ABDC: A\*, ABS: 3)

        **Conference contributions**
        * 4th Operations and Supply Chain Management Symposium: Emerging Technologies and the Industry 5.0, 2026, Sheffield, UK | Organizing committee chair
        * [IEEE TEMSON Global 2025 Conference](https://2025.ieee-temscon-global.org/about/international-program-committee), San Diego, CA, USA (IEEE Technology and Engineering Management Society) | Program committee member
        * 2025 Chartered Institute of Logistics & Transport (CILT) annual Logistics Research Network Conference (LRN) | LRN conference review panel member

        **Journal Reviewers ([Publon/Web of Science](https://www.webofscience.com/wos/author/record/AAX-7454-2020))**
        * Production and Operations Management
        * Journal of Operations Management
        * Journal of Supply Chain Management
        * International Journal of Operations and Production Management
        * Transportation Research Part E: Logistics and Transportation Review
        * IEEE: Transactions on Engineering Management
        * International Journal of Production Research
    design:
      columns: "1"
      spacing:
        padding: ["1.5rem", 0, "1.5rem", 0]
      animation:
        name: fadeInUp

  - block: collection
    id: papers
    content:
      title: "📄 Peer-Reviewed Publications"
      filters:
        folders:
          - publications
        publication_type: "article-journal"
      count: 0
    design:
      view: citation
      spacing:
        padding: ["1.5rem", 0, "1.5rem", 0]
      animation:
        name: fadeInUp

  - block: collection
    id: working-papers
    content:
      title: "✍️ Working Papers"
      filters:
        folders:
          - publications
        publication_type: "manuscript"
      count: 0
    design:
      view: citation
      spacing:
        padding: ["1.5rem", 0, "1.5rem", 0]
      animation:
        name: fadeInUp

  - block: collection
    id: book-chapters
    content:
      title: "📖 Book Chapters"
      filters:
        folders:
          - publications
        publication_type: "chapter"
      count: 0
    design:
      view: citation
      spacing:
        padding: ["1.5rem", 0, "1.5rem", 0]
      animation:
        name: fadeInUp

  - block: collection
    id: talks
    content:
      title: "🎤 Conference Presentations & Talks"
      filters:
        folders:
          - events
    design:
      view: card
      spacing:
        padding: ["1.5rem", 0, "1.5rem", 0]
      animation:
        name: fadeInUp
---
