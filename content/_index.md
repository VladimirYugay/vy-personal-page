---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph. D. Candidate
          company: University of Amsterdam
          company_url: 'https://icai.ai/atlas-lab/'
          location: Amsterdam
          date_start: '2023-04-01'
          date_end: '2027-04-01'
          description: |2-
              Working on 3D Computer Vision under supervision of Martin R. Oswald.
        - title: Deep Learning Engineer
          company: KaiaHealth
          company_url: 'https://kaiahealth.com/'
          location: Munich
          date_start: '2020-10-01'
          date_end: '2023-03-31'
          description: 3D human body reconstruction and synthetic data.
          company_logo: kaia-logo
        - title: Machine Learning Engineer, Intern
          company: TWAICE
          company_url: 'https://www.twaice.com/'
          location: Munich
          date_start: '2020-07-01'
          date_end: '2020-10-31'
          description: Machine learning pipelines.
        - title: Machine Learning Engineer, Part-time
          company: Magazino
          company_url: 'https://www.magazino.eu/'
          location: Munich
          date_start: '2019-07-01'
          date_end: '2020-06-30'
          description: Robots' perception and data pipelines.
        - title: Software Engineer, Intern
          company: Yandex
          company_url: 'https://www.yandex.ru'
          location: Moscow
          date_start: '2018-07-01'
          date_end: '2018-10-31'
          description: Mobile development.                              
    design:
      columns: '2'
---
