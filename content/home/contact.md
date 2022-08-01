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
  email: tssw@leeds.ac.uk
  contact_links:
    - icon: researchgate
      icon_pack: ai
      name: Follow
      link: 'https://www.researchgate.net/profile/Sijin-Wu'
    - icon: linkedin
      icon_pack: fab
      name: Follow
      link: 'linkedin.com/in/sijin-wu-0485911b7'

design:
  columns: '2'
---
