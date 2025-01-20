---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Neural Engineering 
        in Epilepsy Lab
      image:
        filename: pizza.jpg
      text: |
        <br>
        
        Our lab is dedicated to developing better technology to help understand and control epilepsy. Dr. Stacey is a clinical epileptologist and spends the majority of his time doing neural engineering research. The lab uses a combination of electrophysiology, machine learning, signal processing, and computational modeling to model and describe neural data. Data for these projects are acquired from a large database of human patients, an ongoing clinical study in patients undergoing surgical implantation of electrodes, and several outside collaborations in other models. The lab is specifically researching the relationship of high frequency oscillations with seizure mechanisms, developing methods to target and stimulate the brain to stop seizures, and methods to quantify seizure dynamics.
  
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: painting.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Representative Publication
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
