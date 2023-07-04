---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

# blocks and their usage can be found here: https://wowchemy.com/blocks/
sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: Research Assistant
  #         company: Deutsche Telekom Chair of Communication Networks, TU Dresden
  #         company_url: 'https://cn.ifn.et.tu-dresden.de'
  #         # company_logo: comnets_logo
  #         # location: Dresden, Germany
  #         date_start: '2019-10-15'
  #         date_end: '2023-03-28'
  #         description: |2-
  #             * Application of ML/RL to communication networks and transportation systems
  #             * Student Supervision, Coursework
  #             * Acquisition of third-party funds
  #       - title: Working Student
  #         company: Deutsche Telekom MMS
  #         company_url: 'https://www.telekom-mms.com'
  #         # company_logo: telekom
  #         # location: Dresden, Germany
  #         date_start: '2018-04-01'
  #         date_end: '2018-10-31'
  #         description: ML for natural language processing.
  #       - title: Intern
  #         company: Bosch
  #         company_url: 'bosch.de'
  #         # company_logo: telekom
  #         # location: Hildesheim, Germany
  #         date_start: '2015-09-01'
  #         date_end: '2016-03-31'
  #         description: Image processing on dynamic vision sensor.
  #   design:
  #     columns: '2'
  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - news
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
  # - block: collection
  #   id: post
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: collection
    id: recent
    content:
      title: Publications
      count: 5
      # text: |-
      #   {{% callout %}}
      #   [View all publications](./publication/).
      #   {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  # - block: markdown
  #   id: activities
  #   content:
  #     title: Professional Activities
  #     text: |-
  #       ## Reviewing
  #       IEEE Access   
  #       IEEE Systems Journal
  #   design:
  #     columns: 2
  - block: markdown
    id: awards
    content:
      title: Grants & Awards
      text: |-
        ### Awards
        - Prize for outstanding final theses in information and communication technologies of the Saxonian Center of Telecommunication, 2020  
        - IEEE Open Journal of Intelligent Transportation Systems Best Paper Award, 2020  
    design:
      columns: 2
  - block: markdown
    id: review
    content:
      title: Reviewing & Editorial 
      text: |-
        ### Reviewing
        - IEEE Systems Journal (x2)
        - IEEE European Wireless (x2)
    design:
      columns: 2 
  - block: markdown
    id: teaching
    content:
      title: Teaching & Supervision
      text: |-
        ### Teaching
          - Fundamentals of Electrical Engineering 1 (WS20/21)
          - Fundamentals of Electrical Engineering 2 (SS21)
          - Communication Networks 3 (WS20/21, WS21/22)
        ### Student Supervision
          - Xianran Liu - Deep Reinforcement Learning for Handovers in Mobile Networks (Study Thesis)
          - Nerea Fernandez-Sanchez - Joint Optimization of Traffic Signaling and Vehicle Speed Advise in V2I-Enabled Traffic with Deep Reinforcement Learning (Bachelor Thesis)
          - Mao Xinwei - Investigation of Smart Routing and Queue Management for on the Fly Processing (Master Thesis)
          - Adrian Bretschneider-Perez - AI aided robot remote control (Diploma Thesis)
          - Hassine Chahed - Autonomous Transfer Learning Through the Use of a Context-Driven Artifact Description Language (Internship)
          - Yueyue Gao - Investigation of Deep Reinforcement Learning for Routing in Software-defined Networks (Master Thesis)
          - Robert Voelckner - Reinforcement Learning for Joint Control of Vehicles and Infrastructure in V2I-Enabled Traffic (Master Thesis)
          - Xianran Liu - The Impact of Network Latency on Autonomous Traffic Controlled by Deep Reinforcement Learning (Diploma Thesis)


    design:
      columns: 2 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please write me a message if you are interested in working with me.
      # Contact (add or remove contact options as necessary)
      email: jbusch AT lasr DOT org
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
        # - icon: twitter
        #   icon_pack: fab
        #   name: DM Me
        #   link: 'https://twitter.com/Twitter'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      # autolink: true
      # # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'

---
