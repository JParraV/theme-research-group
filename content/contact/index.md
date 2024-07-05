---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        If you want to collaborate with us or have a good research idea, don't hesitate to get in touch with us.
      email: jonathan.parra@ucr.ac.cr
      phone: +506 25118317
      address:
        street: Ciudad Universitaria Rodrigo Facio
        city: San Pedro
        region: SJ
        postcode: '11501-2060'
        country: Costa Rica
        country_code: CR
      coordinates:
        latitude: '9.938764438283627'
        longitude: '-84.05004795494986'
      directions: Laboratorio de Farmacología, Facultad de Farmacia
      office_hours:
        - 'Tuesday 13:00 to 17:00'
        - 'Thursday 13:00 to 17:00'
      appointment_url: 'mailto:jonathan.parra@ucr.ac.cr'
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
