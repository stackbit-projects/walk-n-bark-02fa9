---
title: Contact
sections:
  - type: hero_section
    title: Contact Me
    subtitle: Fill out the form below and I will get in touch with you shortly.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ## Schedule Your Dog Walk!


      Put your email, name, and when you want us to walk your doggo! We will get
      to you as soon as possible and if your time doesn't fit in our avalible
      time we will try to reschedule. And also first walk is free!
    content_align: left
    form_position: left
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: tel
        name: Phone Number
        label: Phone Number
        default_value: Your phone number
        options: []
        is_required: false
        type: form_field
      - input_type: text
        name: Your Dogs Name
        label: Your Dogs Name
        default_value: Your Dog's Name
        options: []
        is_required: false
        type: form_field
      - input_type: textarea
        name: What Day? What time?
        label: What Day? What time?
        default_value: Your message
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: /images/magenta-olive.jpg
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
