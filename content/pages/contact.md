---
type: PageLayout
title: Contact
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: We'd love to hear from you
      color: text-dark
    subtitle: 'We''re happy to hear from clients, partners and collaborators.'
    text: |
      Address: 590 Chiswick High Road, London, UK

      Phone: +44 7774348345

      Email: <gaoyuyao88@gmail.com>
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextFormControl
          name: Company
          label: Company
          hideLabel: true
          placeholder: Company
          isRequired: true
          width: full
        - type: TextFormControl
          name: Phone
          label: Phone
          hideLabel: true
          placeholder: Phone
          isRequired: true
          width: full
        - type: SelectFormControl
          name: Design requirements
          label: Design requirements
          hideLabel: false
          defaultValue: Please choose...
          options:
            - Redesign a website or App
            - Design a new website or App
            - Branding or rebranding
            - B2B SaaS
            - 'Development, ongoing support and maintenance'
          isRequired: false
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: Contact
isDraft: false
seo:
  type: Seo
  metaTitle: 'Talk to YG Design, '
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
