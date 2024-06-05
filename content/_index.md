---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing


sections:
  - block: hero
    content:
      title: |
        SINNet 
      image:
        filename: icon.png
      text: |
        Socio-Inspired Neural networks 
        Research Project funded by ANR
  - block: markdown
    content:
      title: Abstract
      subtitle: My subtitle
      text: blablabla
 
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  


  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'
---
