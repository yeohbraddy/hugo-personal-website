---
widget: contact
widget_id: contact
headless: true
weight: 130
title: Contact
subtitle: null
content:
  form:
    provider: netlify
    formspree:
      ? id
    netlify:
      captcha: false
  autolink: true
  office_hours:
    - Monday 10:00 to 13:00
    - Wednesday 09:00 to 10:00
  phone: 888 888 88 88
  appointment_url: https://calendly.com
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  address:
    street: 450 Serra Mall
    city: Stanford
    region: CA
    postcode: "94305"
    country: United States
    country_code: US
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: https://twitter.com/Twitter
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: https://zoom.com
  coordinates:
    latitude: "37.4275"
    longitude: "-122.1697"
  email: test@example.org
design:
  columns: "2"
---
widget: contact
headless: true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...
title: Contact Me
subtitle: ''
weight: 10

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
  email: test@example.org
  phone: 888 888 88 88
  address:
    street: 450 Serra Mall
    city: Stanford
    region: CA
    postcode: '94305'
    country: United States
    country_code: US
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'
