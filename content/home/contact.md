---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
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
  email: hervey.hw@hotmail.com
  address:
    street: 163 Xianlin Road
    city: Nanjing
    region: Qixia
    postcode: '210023'
    country: China
  directions: Building of Computer Science and Technology
  # appointment_url: 'https://calendly.com'
  # contact_links:
  #   - icon: twitter
  #     icon_pack: fab
  #     name: DM Me
  #     link: 'https://twitter.com/Twitter'
  #   - icon: video
  #     icon_pack: fas
  #     name: Zoom Me
  #     link: 'https://zoom.com'
  coordiantes:
    latitude: '32.1160'
    longitude: '118.9592'

design:
  columns: '2'
---
