---
type: PageLayout
title: Inhalt
sections:
  - type: PricingSection
    title:
      type: TitleBlock
      text: Flexible Pricing
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: This is the subtitle for the pricing section
    plans:
      - type: PricingPlan
        title: Professional
        price: $99
        details: per month
        description: >-
          Sed ut perspiciatis unde omnis, iste natus error sit voluptatem
          accusantium doloremque.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
        actions:
          - type: Button
            label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
      - type: PricingPlan
        title: Enterprise
        price: Custom
        details: per month
        description: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
          - Feature five
        image:
          type: ImageBlock
          url: /images/abstract-feature3.svg
          altText: Pricing plan 3
        actions:
          - type: Button
            label: Contact us
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: ''
      color: text-dark
    subtitle: ''
    text: ''
    actions: []
    media:
      type: ImageBlock
      url: /images/pexels-jan-van-der-wolf-11680885-19013463.jpg
      altText: Unblock your team boost your time to production preview
      elementId: ''
    badge:
      type: Badge
      label: Fachzentrum für psychosomatische Medizin und Psychotherapie
      color: text-primary
      styles:
        self:
          fontWeight: 400
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-6
          - pl-6
          - pb-6
          - pr-6
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
slug: /Inhalt
seo:
  type: Seo
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  metaTags: []
---
