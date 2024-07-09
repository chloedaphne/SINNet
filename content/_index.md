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
      title: Abstract2
      text: SINNet proposes a paradigm shift for rendering conversational systems and social robotics a more acceptable and trustworthy technology even when using deep learning approaches. It will focus on the verbal component of the interaction, will target the agent-user social relationship, and model the behaviors indexing the state of the social relationship between agent and user, going thus beyond the analysis of the user’s positive and negative sentiments. It implies developing easy-to-adapt and easy-to-explain neural models able to analyze the user’s behavior contributing to user- agent co-construction processes such as the ones characterizing the rapport with the agent, or the trust and affiliation in the agent, as well as to generate the agent’s answer fostering the user-agent social relationship. This SINNet project will establish interdisciplinarity as a core challenge by providing a shared formalism between complex (e.g., psychological or socio- linguistic) theories of social interactions and the underlying formalism in deep learning and language models.
 
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
