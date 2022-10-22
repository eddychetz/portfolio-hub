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
      captcha: true

  # Contact details (edit or remove options as required)
  email: eddychetz@gmail.com
  phone: +27 67 972 2872
  address:
    street: 4B Greyilla Avenue
    city: Kempton Park
    region: Gauteng
    postcode: '1619'
    country: South Africa
    country_code: ZA
  coordinates:
    latitude: ''
    longitude: ''
  directions: 
  office_hours:
    - 'Monday 08:00 to 17:00'
    - 'Wednesday 09:00 to 14:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'

design:
  columns: '2'
---
