---
# Leave the homepage title empty to use the site title
title:
date: 2023-02-18
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
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
        - title : Data Engineer
          company : Chura DATA inc.
          company_url : https://churadata.okinawa/
          location : Okinawa Japan
          date_start : '2023-07-16'
          date_end : 
          description : working at Nagoya remotely
        - title : A full stack Engineer
          company : T-virtuoso (Freelancer)
          company_url : 
          location : Nagoya Japan
          date_start : '2023-02-01'
          date_end : '2023-07-15'
          description : 
        - title : Engineer / Architect
          company : SCSK corporation
          company_url : https://www.scsk.jp/index_en.html
          location : Nagoya Japan
          date_start : '2021-04-01'
          date_end : '2023-01-31'
          description : |2-
            * Mobility System
            * AWS Lambda
            * AWS CodeStar
        - title : Engineer
          company : PayPay Corporation
          company_url : https://paypay.ne.jp/
          location : Tokyo Japan
          date_start : '2020-09-01'
          date_end : '2021-03-31'
          description : |2-
            * Java
            * Spring boot
            * AWS
            * Kafka
        - title : A full stack Engineer
          company : Freelancer
          company_url : 
          location : Nagoya Japan
          date_start : '2020-05-01'
          date_end : '2020-08-31'
          description : 
        - title : Lead Engineer
          company : ATeam Inc.
          company_url : https://www.a-tm.co.jp/en/
          location : Nagoya Japan
          date_start : '2012-07-01'
          date_end : '2020-04-30'
          description : |2-
            * Machine Learning
            * Game Capture Site
            * SNS
            * Chat
            * EC Site
            * Mobile Game
            * Billing System
            * Member Management System
        - title : Engineer / Architect / Consultant
          company : SCSK corporation
          company_url : https://www.scsk.jp/index_en.html
          location : Nagoya Japan
          date_start : '2007-12-01'
          date_end : '2012-06-30'
          description : |2-
            * Estimating System
            * Trade Management System
            * Project Management Consulting
            * Production Management System
            * Member Management System
            * Order Management System
            * Sales Management System
        - title : Engineer / Teacher
          company : CSK corporation
          company_url : https://ja.wikipedia.org/wiki/CSK_(%E4%BC%81%E6%A5%AD)
          location : Tokyo Japan
          date_start : '2004-04-01'
          date_end : '2007-11-30'
          description : |2-
            * BPO
            * Developing Framework for own company
            * Teaching .NET Framework
        - title : Programmer
          company : CSK corporation
          company_url : https://ja.wikipedia.org/wiki/CSK_(%E4%BC%81%E6%A5%AD)
          location : Nagoya Japan
          date_start : '1998-03-01'
          date_end : '2004-03-31'
          description : |2-
            * Teaching Java
            * R&D
            * Purchasing Management System
    design:
      columns: '2'
  - block: features
    id: skills_mwapp
    content:
      title: Skills
      subtitle: Mobile/Web App
      items:
        - name : Android
          description : Advanced
        - name : iOS
          description : Advanced
        - name : Ruby on Rails
          description : Intermediate
        - name : Java
          description : Advanced
        - name : Kotlin
          description : Intermediate
        - name : Swift
          description : Advanced
        - name : Ruby
          description : Intermediate
        - name : HTML/CSS
          description : Intermediate
        - name : Javascript
          description : Intermediate
  - block: features
    id: skills_ml
    content:
      title: Skills
      subtitle: ML
      items:
      - name : Python
        description : intermediate
      - name : scikit-learn
        description : intermediate
      - name : jupyterlab
        description : intermediate
  - block: features
    id: skills_game
    content:
      title: Skills
      subtitle: Game
      items:
      - name : Unity
        description : Beginner
      - name : cocos2d-x
        description : Beginner
      - name : C#
        description : intermediate
      - name : XMPP(chat)
        description : Advanced
  - block: features
    id: skills_foundation
    content:
      title: Skills
      subtitle: Foundation
      items:
      - name : Object Oriented
        description : Advanced
      - name : SQL
        description : Advanced
      - name : Linux
        description : intermediate
      - name : AWS
        description : intermediate
      - name : GCP
        description : intermediate
      - name : Git
        description : intermediate
      - name : Network
        description : intermediate
  - block: features
    id: skills_ancience
    content:
      title: Skills
      subtitle: Ancient
      items:
      - name : MS Access
        description : Advanced
      - name : Visual Basic
        description : Advanced
      - name : PHP
        description : Advanced
      - name : Oracle
        description : intermediate
      - name : PL/SQL
        description : intermediate
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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
      view: compact
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
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
        exclude_featured: true
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
---
