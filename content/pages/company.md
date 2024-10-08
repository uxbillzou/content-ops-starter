---
title: Company
slug: /company
sections:
  - title:
      text: A forward-thinking design agency
      color: text-light
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: YG Design
    text: >
      We're a London-based UX/UI design agency that's all about creating awesome
      digital experiences. Our team of talented designers and developers are
      here to help startups, SMEs, and large enterprises with innovative and
      effective design solutions. Our goal is to be a top global UX/UI design
      agency known for our creativity and innovation. We love working together
      to help our clients thrive and succeed!
    actions:
      - label: Free design consultation
        url: /Contact
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    colors: bg-dark-fg-light
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-14
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: auto
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 59
      url: /images/nastuh-abootalebi-eHD8Y1Znfpk-unsplash.jpg
  - title:
      text: Meet the team
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/christiane.json
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedPeopleSection
seo:
  metaTitle: Elevate your brand with smart value
  metaDescription: >-
    premium, enterprises, SMEs, Startups, branding, websites, Apps, Saas, London
    creative digital design agency
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
