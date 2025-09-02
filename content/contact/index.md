---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        The **Smart Grids Laboratory** focuses on **distribution network planning**, **integration of distributed energy resources (DERs)** such as PV and BESS, and the application of **optimization algorithms**. Our research also covers **renewable energy topics** and **Industry 4.0**, fostering collaboration with academia and the power sector through applied projects and student training.

        **Location:** EPUSP – Electrical Engineering Building – **A2-38**, at the **University of São Paulo (USP)**, Butantã campus.
      email: gustavo.morales-espinoza@usp.br
      phone: '+55 11 3091-5260'
      address:
        street: 'Av. Prof. Luciano Gualberto, travessa 3, nº 158 – Electrical Engineering Building (A2-38)'
        city: 'São Paulo'
        region: 'SP'
        postcode: '05508-010'
        country: 'Brazil'
        country_code: BR
      directions: 'Enter the Electrical Engineering Building and go to Lab A2-38.'
      office_hours:
        - 'Building hours: usually open until 11:00 PM'
      appointment_url: ''
      contact_links:
        - icon: envelope
          icon_pack: fas
          name: 'Prof. Juan Carlos Cebrian'
          link: 'mailto:juan.cebrian@usp.br'
        - icon: envelope
          icon_pack: fas
          name: 'Gustavo Morales Espinoza'
          link: 'mailto:gustavo.morales-espinoza@usp.br'
        - icon: globe
          icon_pack: fas
          name: 'C2D Website'
          link: 'https://c2d.poli.usp.br'
    
      # Automatically link email and phone
      autolink: true
    
      # Contact form provider (optional)
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
