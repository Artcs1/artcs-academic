---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: I am researcher with interest in 2D-3D object detection, spherical images and natural language processing. I received my Master from [Institute of Informatics](https://www.inf.ufrgs.br/ppgc/) at the [Federal University of Rio Grande do Sul](http://www.ufrgs.br/english/home). My advisor was Prof. [Claudio Rosito Jung](https://www.inf.ufrgs.br/~crjung/). I mainly worked in 2D oriented object detection. I got my undergrad from [National University of Trujillo](https://inf.unitru.edu.pe/), with a major in computer science.
  - block: experience
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
        - title: Research Assistant
          company: Federal University Of Rio Grande do Sul
          company_url: 'https://www.inf.ufrgs.br/site/'
          company_logo: org-x
          location: Brazil
          date_start: '2020-01-01'
          date_end: ''
          description: Research in object detection and spherical images.
        - title: Volunteer
          company: HackSpace
          company_url: 'https://hackspace.pe/'
          company_logo: org-x
          location: Peru
          date_start: '2017-01-01'
          date_end: '2018-01-01'
          description: Volunteer.
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://coursera.org/share/11cd879c3414dff908bac72c6f9aeddd
          date_end: ''
          date_start: '2019-06-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Deep Learning specialization
          url: ''
        - certificate_url: https://coursera.org/share/756671a72e163b9edb4109bfe86cb77e
          date_end: ''
          date_start: '2019-03-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Natural Language Processing
          url: ''
        - certificate_url: https://coursera.org/share/b5d08e53aa7755abb968cf1bb0288547
          date_end: ''
          date_start: '2019-01-25'
          description: ''
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Machine Learning
          url: ''
    design:
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      email: ju.jeffri.v@gmail.com
      address:
        street: TBD
        city: TBD
        region: TBD
        postcode: TBD
        country: TBD
        country_code: TBD
    design:
      columns: '2'
---
