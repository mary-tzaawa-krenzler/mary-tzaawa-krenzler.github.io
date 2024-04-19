---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-04-20
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
#  - block: collection
#    content:
#      title: Publications
#      text: |-
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
  - block: collection
    id: workingpaper
    content:
      title: Working Papers
      text: |-
      filters:
        folders:
          - publication2
        exclude_featured: true
    design:
      columns: '2'
      view: compact
  - block: collection
    id: progress
    content:
      title: Work in progress
      text: |-
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: compact
#  - block: experience
#    content:
#      title: Experience
#      # Date format for experience
#      #   Refer to https://docs.hugoblox.com/customization/#date-format
#      date_format: Jan 2006
#      # Experiences.
#      #   Add/remove as many `experience` items below as you like.
#      #   Required fields are `title`, `company`, and `date_start`.
#      #   Leave `date_end` empty if it's your current employer.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - title: CEO
#          company: GenCoin
#          company_url: ''
#          company_logo: org-gc
#          location: California
#          date_start: '2021-01-01'
#          date_end: ''
#          description: |2-
#              Responsibilities include:
#
#              * Analysing
#              * Modelling
#              * Deploying
#        - title: Professor of Semiconductor Physics
#          company: University X
#          company_url: ''
#          company_logo: org-x
#          location: California
#          date_start: '2016-01-01'
#          date_end: '2020-12-31'
#          description: Taught electronic engineering and researched semiconductor physics.
#    design:
#      columns: '2'
  - block: portfolio
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons: 
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: 2
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: tzaawakr@its.uni-frankfurt.de
      phone:  
      appointment_url:  
      address:
        street: Theodor-W.-Adorno Platz 3
        city: Frankfurt am Main 
        region: 
        postcode: '60629'
        country:  Germany
        country_code: DE
      directions:
      office_hours:       
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: 
        longitude:  
      contact_links:
        - icon: 
          icon_pack: 
          name:  
          link: 
        - icon:
          icon_pack: 
          name: 
          link: 
        - icon: 
          icon_pack:
          name:
          link:
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
