---
title: Careers
slug: careers
sections:
  - title:
      text: A team that works closely together
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Section subtitle
    text: >
      There are many variations of passages of Lorem Ipsum available, but the
      majority have suffered alteration in some form, by injected humour, or
      randomised words which don't look even slightly believable. If you are
      going to use a passage of Lorem Ipsum, you need to be sure there isn't
      anything embarrassing hidden in the middle of text.
    actions:
      - label: Contact For positions
        url: /muntasir1710@gmail.com
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    colors: bg-neutral-fg-dark
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
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/Sot one.png
  - title:
      text: Meet Our Team
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
      - content/data/person6.json
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
  - title:
      text: Open Positions
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Contact Us For your Skills
    items: []
    actions:
      - label: Send Resume
        url: /muntasir1710@gmail.com
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
