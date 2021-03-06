---
title: Contact
sections:
  - type: hero_section
    title: Contact Us
    subtitle: Fill out the form below and we will get in touch with you.
    align: center
    padding_top: medium
    padding_bottom: medium
    background_color: none
  - type: form_section
    content: >
      ### Dates


      Ensure you include the dates that you require.


      ### Size of party


      Please be sure to include the size of your party and remember to include
      any dogs!
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
        name: phone
        label: Phone number
        default_value: Your mobile phone number
        options: []
        is_required: true
      - input_type: number
        name: Size of party
        label: Size of party
        options:
          - lorem-ipsum
        is_required: true
        default_value: How many people?
      - input_type: checkbox
        name: Dogs
        label: Will you be bringing a dog? (maximum 2 allowed)
        default_value: Will you be bringing any dog(s)? (maximum 2 allowed)
        options: []
        is_required: false
      - input_type: text
        name: Dates required
        label: Dates required
        default_value: Please enter the date you require
        options:
          - lorem-ipsum
        is_required: true
      - input_type: textarea
        name: message
        label: Message
        default_value: Please provide any further information relevant to your booking.
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: none
    background_image: images/watercolor.png
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
