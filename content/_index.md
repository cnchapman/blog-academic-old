---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 
      icon: user-group
      icon_pack: fas
      name: UX Research
    - description: 
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 
      icon: r-project
      icon_pack: fab
      name: R

    title: Skills
- block: experience
  active: false
  content:
    date_format: Jan 2006
    items:
    - company: Amazon Lab 126
      company_logo: 
      company_url: ""
      date_end: ""
      date_start: "2022-06-22"
      location: Seattle
      title: Principal UX Researcher
      
    - company: Google
      company_logo: 
      company_url: ""
      date_end: "2022-06-15"
      date_start: "2012-01-30"
      location: New York 
      title: Staff Quantitative UX Researcher
    - company: Microsoft
      company_logo: 
      company_url: ""
      date_end: "2011-11-15"
      date_start: "2000-10-30"
      location: Redmond
      title: Senior UX Researcher
    title: Experience
  design:
    columns: "2"

- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  active: false
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  active: false
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  active: false
  content:
    address:
      city: Stanford
      country: United States
      country_code: US
      postcode: "94305"
      region: CA
      street: 450 Serra Mall
    appointment_url: https://calendly.com
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/Twitter
      name: DM Me
    - icon: skype
      icon_pack: fab
      link: skype:echo123?call
      name: Skype Me
    - icon: video
      icon_pack: fas
      link: https://zoom.com
      name: Zoom Me
    directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: test@example.org
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Monday 10:00 to 13:00
    - Wednesday 09:00 to 10:00
    phone: 888 888 88 88
    subtitle: null
    text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
      ut magna et, vehicula efficitur enim.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
