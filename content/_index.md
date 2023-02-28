---
date: "2023-02-27"
sections:
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

- block: about.avatar
  content:
    text: null
    username: admin
  id: about
  
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Amazon Lab126
      company_logo: 
      company_url: ""
      date_end: ""
      date_start: "2022-06-22"
      location: Seattle
      title: Principal UX Researcher

    - company: Quantitative UX Association / Quant UX Conference
      company_logo: 
      company_url: "https://quantuxcon.org"
      date_end: ""
      date_start: "2021-10-01"
      location: Seattle
      title: Founder
      
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
    title: Positions
  design:
    columns: "2"

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
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"

title: null
type: landing
---
