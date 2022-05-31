---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90

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
  email: g.zhang@usst.edu.cn
  # phone: 888 888 88 88
  address:
    street: No.334 Jungong Road, Yangpu District
    city: Shanghai
    # region: CA
    postcode: '200093'
    country: China
    country_code: CN
  coordinates:
    latitude: '31.2870'
    longitude: '121.5580'
  directions: Enter Business School Building A and take the stairs to Office 1006 on Floor 10
  office_hours:
    - 'Monday 10:00 to 18:00'
    - 'Wednesday 09:00 to 18:00'
  # appointment_url: 'https://calendly.com'
  # contact_links:
  #  - icon: twitter
  #    icon_pack: fab
  #    name: DM Me
  #    link: 'https://twitter.com/Twitter'
  #  - icon: video
  #    icon_pack: fas
  #    name: Zoom Me
  #    link: 'https://zoom.com'

design:
  columns: '2'
---
