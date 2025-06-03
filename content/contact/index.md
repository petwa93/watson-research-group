---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        We're always keen to discuss our work, science and any potential collaborations we might be able to find. Just complete your details below and we will be in touch.
      email: peter@watsonlaserlab.com
      #phone: 888 888 88 88
      address:
        street: 'Kent St, Bentley'
        city: Perth
        region: Western Australia
        postcode: '6102'
        country: Australia
        country_code: AUS
      coordinates:
        latitude: '-32.01183333'
        longitude: '115.8928056'
      directions: 'Lab: Building 500'
      #  - 'Office: Building 204'
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
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
          captcha: true
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
          filename: syrah_laser.jpg
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
