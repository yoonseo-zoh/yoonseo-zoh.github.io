---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Yoonseo Zoh
      image:
        filename: hero-academic.png
      cta:
        label: 'How to pronounce my name'
        url: http://ipa-reader.xyz/?text=juns%C9%94%3A&voice=Ivy
      text: |-
        I’m a PhD student in Psychology at Princeton, aspring to be a social neuroscientist who studies human’s social & moral minds 💜 

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  #- block: features
  #  content:
  #    title: Skills
  #    items:
  #      - name: R
  #        description: 90%
  #        icon: r-project
  #        icon_pack: fab
  #      - name: Statistics
  #        description: 100%
  #        icon: chart-line
  #        icon_pack: fas
  #      - name: Photography
  #        description: 10%
  #        icon: camera-retro
  #        icon_pack: fas
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
        - title: Graduate Student
          company: Princeton University
          company_url: ''
          company_logo: ''
          location: Princeton, NJ
          date_start: '2022-09-01'
          date_end: ''
          #description: |2-

        - title: Graduate Student
          company: Yale University
          company_url: ''
          company_logo: ''
          location: New Haven, CT
          date_start: '2020-08-01'
          date_end: '2022-08-31'
          #description: Taught electronic engineering and #researched semiconductor physics.
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
        - certificate_url: 
          date_end: '2024-06-01'
          date_start: '2023-09-01'
          description: ''
          organization: Kahneman-Treisman Center for Behavioral Science & Public Policy
          organization_url: https://behavioralpolicy.princeton.edu/
          title: The G. Mason Morfit ’97 Fellowship
          url: ''
        - certificate_url: 
          date_end: '2025-09-01'
          date_start: '2019-09-01'
          description: 
          organization: Korea Foundation for Advanced Studies
          organization_url: https://eng.kfas.or.kr/
          title: Scholarship for Doctoral Study Abroad
          url: 
    design:
      columns: '2'
  #- block: collection
  #  id: posts
  #  content:
  #    title: Recent Posts
  #    subtitle: ''
  #    text: ''
  #    # Choose how many pages you would like to display #(0 = all pages)
 #     count: 5
 #     # Filter on criteria
 #     filters:
 #       folders:
 #         - post
 #      author: ""
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
      # Choose a layout view
 #     view: compact
 #     columns: '2'
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  #- block: markdown
  #  content:
  #    title: Gallery
  #    subtitle: ''
  #    text: |-
  #      {{< gallery album="demo" >}}
  #  design:
  #    columns: '1'
  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card
  #- block: collection
  #  content:
  #    title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: true
  #  design:
  #    columns: '2'
  #    view: citation
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        
      # Contact (add or remove contact options as necessary)
      email: yoonseo.zoh@princeton.edu
    #  phone: 888 888 88 88
    #  appointment_url: 'https://calendly.com'
      address:
        street: Peretsman Scully Hall, 330
        city: Princeton
        region: NJ
        postcode: '08540'
        country: United States
        country_code: US
#      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/zohyos7'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
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
