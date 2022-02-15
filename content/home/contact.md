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
  email: jt + last name @ gmail dot com
  address:
    region: NJ
    country: United States
    country_code: US
  appointment_url: 'https://calendly.com/jtpatchett'
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Connect with me
      link: 'https://www.linkedin.com/in/joe-patchett/'


design:
  columns: '2'
---
