---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

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
  email: mstackh@uwo.ca
  phone: xxx-xxx-xxxx
  address:
    street: 1151
    city: London
    region: Ontario
    postcode: 'N6A 3K7'
    country: Canada
    country_code: CA
  coordinates:
    latitude: '43.0096'
    longitude: '81.2737'
  directions: Social Science Centre, Office 5225-D
  office_hours:
    - 'Monday through Friday - 9:00 to 5:00, EST'
  appointment_url: 'https://calendly.com'
  #contact_links:
   # - icon: twitter
    #  icon_pack: fab
     # name: DM Me
    #  link: 'https://twitter.com/Twitter'
    #- icon: video
     # icon_pack: fas
      #name: Zoom Me
      #link: 'https://zoom.com'

design:
  columns: '2'
---
