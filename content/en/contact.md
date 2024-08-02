---
title: Contact
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: 'Contact us'
      text: "Fill out the form below, and we'll contact you shortly"
      email: operations@suresta.com
      phone: +34 641 49 41 53
      appointment_url: 'https://calendly.com'
      address:
        street: Escriptor Abu Salt, 1
        city: Valencia
        region: Valencia
        postcode: '46009'
        country: Spain
        country_code: ES
      directions: Enter Building 1 and take the stairs to Office 10 on Floor 2
      office_hours:
        - 'Monday to Friday 09:00 to 17:00'
      contact_links:
        - icon: x
          icon_pack: brands
          name: DM Us
          link: 'https://twitter.com/suresta'
      autolink: true
      form:
        provider: netlify
        formspree:
          id: ''
        netlify:
          captcha: false
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      required_fields: ['first_name', 'last_name', 'email', 'subject', 'message', 'company']
    design:
      columns: '1'
---
