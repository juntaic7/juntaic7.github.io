---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: iStock-962362664.jpg
          filters:
            brightness: 0.7
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
      #   - statistic: "15"
      #     description: |
      #       Publications
      #   - statistic: "1,000+"
      #     description: |
      #       Citations
      #   - statistic: "78"
      #     description: |
      #       h-index
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: 'Welcome 👋'
      subtitle: ''
      text: |-
        I am Juntai Cao, an MSc student in Computer Science at the University of British Columbia, advised by [Jiarui Ding](https://www.cs.ubc.ca/~jiaruid/).

        My research centers on large language models, with a focus on:
        - AI agents and tool-using systems
        - model interpretability and reliability
        - efficient LLM inference and deployment

        I am always happy to discuss research ideas and potential collaborations.

    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: news
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
