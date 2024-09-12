---
title: Company
slug: /company/
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
      We are a London-based UX/UI design agency offering high-quality,
      user-centric design solutions tailored to businesses worldwide. We
      leverage a team of experienced designers and developers to provide
      innovative and cost-effective digital design services for startups, SMEs,
      and large enterprises. We aim to become a leading global UX/UI design
      agency known for excellence, creativity, and innovation, fostering a
      collaborative environment where talent thrives and clients succeed.
    actions:
      - label: Free design consultation
        url: /
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
          - pb-40
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
      subtitle:
        textAlign: center
    type: FeaturedPeopleSection
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
