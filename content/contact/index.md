---
title: Kontakt

type: landing

sections:
  - block: contact
    content:
      title: Kontakt
      text: |-
        Falls ihr Anregung oder Fragen habt, schreibt uns gerne. 
      email: scienceforus25@gmail.com
      address:
        street: Rüdesheimer Straße 50
        city: Berlin
        postcode: '14197'
        country: Deutschland
        country_code: DE
      #coordinates:
      #  latitude: '37.4275'
      #  longitude: '-122.1697'
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
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
