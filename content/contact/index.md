---
title: Contact
date: 2026-07-01

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        Hi, for any more details, contact me on my 
      email: ashasv@tripp.iitd.ac.in
      address:
        street: MS 804
        city: IIT Delhi
        region: Delhi
        postcode: '110016'
        country: India
        country_code: IN
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
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
          filename: contact.jpg
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
