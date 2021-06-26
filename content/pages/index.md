---
title: Home
sections:
  - type: hero_section
    title: Walk n' Bark
    subtitle: >-
      Hello! Do you want to relax but your pooch wont let you be? My business
      will help you with that! My name is Daniel and me and my friend's will be
      happy to walk your dog for a reasonable price. Me and my team will help
      you with taking your furry friend outside for 30-60 minutes!
    actions:
      - label: Contact Me
        url: /contact
        style: primary
    image: /images/iStock-1143749718.jpg
    image_alt: A smiling woman
    media_position: right
    media_width: fifty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 12
    background_image: /images/doggo foot.jpg
  - type: features_section
    title: What we do
    features:
      - title: How we do it
        subtitle: How we spend time with your dog
        content: >
          We will take your canine buddy on 15-30 minute walk or 30-60 minute
          walk (you chose)  so your dog will come back happy from breathing
          fresh air and running around. No job is too big or small!
        actions: []
        image: /images/happy shober.jpg
        image_alt: Feature 1 illustration
        media_position: right
        media_width: sixty
      - title: Our needs
        subtitle: What we need for your dog to have a good time!
        content: >
          it would be nice if you could provide us with poop bags, leash, and
          treats so we can take care of your cute dog. Also please make sure
          that your dog is not aggresive to other people. Thank you!
        actions: []
        image: /images/square-coriander.jpg
        image_alt: Feature 2 illustration
        media_position: left
        media_width: sixty
        align: left
      - title: Our prices
        subtitle: What we charge you
        content: "For 15-30 minute walks you pay 5$ and 30-60 minute walks cost 10$. But if this is your first time your first walk is free! Thank you for choosing Walk n' Bark.\U0001F436\n"
        actions: []
        image: /images/rich doggo.jpg
        image_alt: Feature 3 illustration
        media_position: right
        media_width: sixty
    feature_padding_vert: large
    align: center
    background_color: none
  - type: form_section
    content: >
      ## Schedule your dog walk!


      Put your email, name, and when you want us to walk your doggo! We will get
      to you as soon as possible and if your time doesn't fit in our avalible
      time we will try to reschedule. And also first walk is free!
    content_align: left
    form_position: right
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
        label: Phone Number
        options: []
        is_required: false
        type: form_field
        default_value: Your phone number
        name: Phone Number
      - input_type: text
        name: Day
        label: Day
        default_value: Day
        options: []
        is_required: true
        type: form_field
      - input_type: text
        name: Time
        label: Time
        default_value: Time
        options: []
        is_required: true
        type: form_field
      - input_type: text
        name: How can I find you (your address)
        label: How can I find you (Your address)
        options: []
        is_required: false
        type: form_field
        default_value: Address
      - input_type: textarea
        name: message
        label: Comments
        default_value: Your message
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: primary
    background_image: /images/great-daffodil.jpg
    background_image_repeat: repeat
    background_image_size: contain
    background_image_opacity: 8
seo:
  title: Walk and Bark
  description: >-
    Need to walk your dog, but don't have time? We are here to help you!
    Schedule your next walk with us
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: 'Walk and Bark, Dog Walking Services'
      keyName: property
    - name: 'og:description'
      value: >-
        Need to walk your dog, but don't have time? We are here to help you!
        Schedule your next walk with us.
      keyName: property
    - name: 'og:image'
      value: /_static/app-assets/images/FrontFront.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: 'Walk and Bark, Dog Walking Services'
    - name: 'twitter:description'
      value: >-
        Need to walk your dog, but don't have time? We are here to help you!
        Schedule your next walk with us
    - name: 'twitter:image'
      value: /_static/app-assets/images/magical-octopus.png
      relativeUrl: true
layout: advanced
---
