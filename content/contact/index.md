---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        If you’re interested in our research laboratory and would like to learn more about our work, collaborate, or have any inquiries, we’d love to hear from you! We look forward to connecting with you and exploring opportunities together.
      email: wstacey@umich.edu
      #phone: 888 888 88 88B10-A187, 
      address:
        street: NCRC 2800 Plymouth
        city: Ann Arbor
        region: MI
        postcode: '48104'
        country: United States
        country_code: US
      coordinates:
        latitude: '42.2998'
        longitude: '83.7066'
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
       # - 'Monday 10:00 to 13:00'
       # - 'Wednesday 09:00 to 10:00'
      #appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
          filename: corona.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
