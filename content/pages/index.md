---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Design your digital production with us
      color: text-light
      type: TitleBlock
    subtitle: About YG London
    text: >
      Our mission is to deliver excellent UX/UI design solutions that improve
      user experiences and boost business growth. We are dedicated to creating
      innovative, culturally relevant, and visually compelling designs that meet
      our clients' evolving needs while ensuring affordability and high quality.
    actions: []
    media:
      url: >-
        /images/billzou_sketch_of_website_structure_for_YGdesign_in_the_style_o_0199e72d-07c7-4d37-9daf-5914b6396fff
        1.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: This is YG
      color: text-dark
      type: Badge
    elementId: ''
    colors: bg-dark-fg-light
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      text: Our Services
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: User Experience (UX) Design
        subtitle: Websites/mobile apps/softwares
        text: >
          Conduct comprehensive user research and usability testing to develop
          effective design strategies, wireframing & prototyping, and
          interaction design.
        actions: []
        elementId: null
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
            borderColor: border-dark
            borderWidth: 0
            borderStyle: none
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/5731725541505_.pic.jpg
          styles:
            self:
              borderRadius: medium
      - title: User Interface (UI) Design
        subtitle: Websites/mobile apps/softwares
        text: >
          Create visually appealing and user-friendly interfaces that enhance
          the overall user experience. Continuously improve based on user
          feedback and analytics to meet user needs.
        image:
          url: /images/lala-azizli-Uxw-MF_uDGg-unsplash.jpg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Custom Solutions
        subtitle: Websites/mobile apps/softwares
        text: >
          Offering customised services based on specific client needs, combining
          elements from different service categories. Handling the entire design
          process from concept to delivery, covering all aspects of UX/UI,
          branding, and development.
        image:
          url: /images/headway-5QgIuuBxKwM-unsplash.jpg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: All services
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: ''
      color: text-light
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - subtitle: Brands have worked with us
    images:
      - url: /images/Frame 2116674813.jpg
        altText: Wellster logo
        type: ImageBlock
      - altText: Vise logo
        type: ImageBlock
      - altText: Telus logo
        type: ImageBlock
      - url: /images/Frame 2116674811.jpg
        altText: Contentful logo
        type: ImageBlock
      - url: /images/Frame 2116674812.jpg
        altText: Sanity logo
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
  - type: GenericSection
    title:
      type: TitleBlock
      text: A design consultation is on us
      color: text-light
    subtitle: ''
    text: >
      Get a free consultation that brings your business ideas closer to
      production.
    actions: []
    media:
      type: ImageBlock
      url: /images/ux-store-ukeUH3KbMWU-unsplash.jpg
      altText: Dope design preview
    colors: bg-dark-fg-light
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
        justifyContent: flex-start
        padding:
          - pl-16
          - pt-16
          - pb-16
          - pr-16
        margin:
          - ml-0
          - mr-3
          - mt-0
          - mb-0
  - title:
      text: Make your design ideas come true
      color: text-dark
      type: TitleBlock
    subtitle: Book a free consultation with us today
    text: |
      Address: 590 Chiswick High Road, London, UK

      Phone: +44 7774348345

      Email: <gaoyuyao88@gmail.com>
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - type: TextFormControl
          name: Company name
          label: Company name
          hideLabel: true
          placeholder: Company name
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
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
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
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-dark
      type: Badge
    colors: bg-dark-fg-light
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
