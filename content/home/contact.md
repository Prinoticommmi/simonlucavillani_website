---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact Me
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: simon.luca.villani@gmail.com
  phone: +39 346 515 9009
  address:
    street: Via Ambrogio Binda, 56
    city: Milan
    postcode: '20143'
    country: Italy
    country_code: IT
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Link with Me
      link: 'https://www.linkedin.com/in/simon-luca-villani-403abb176/'

design:
  columns: '2'
---
