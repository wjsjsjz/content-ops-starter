---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Welcome to Custom T's
      color: text-dark
    subtitle: ''
    text: |
      Click below to open the design tool and create your austom shirt.
    actions:
      - type: Button
        label: Shop
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
        showIcon: false
    media:
      type: ImageBlock
      url: /images/1000007243_1764780759-removebg-preview (1).png
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Make your own shirt
      color: text-dark
    subtitle: ''
    text: |
      Click below to open the design tool and create your custom shirt.
    actions:
      - type: Button
        label: Make own shirt
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
    media:
      type: ImageBlock
      url: /images/hero2.svg
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Items on sale
      color: text-dark
      styles:
        self:
          textAlign: left
    items:
      - type: FeaturedItem
        title: Faux Fur Throw
        subtitle: $ 88 – $ 176
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
            textAlign: left
            borderRadius: none
            flexDirection: col
            justifyContent: center
      - type: FeaturedItem
        title: Cotton Knit Throws
        subtitle: $ 44.99 – $ 90
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Cotton Knit Throws
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Chunky Cotton Knit Throw
        subtitle: $117
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Chunky Cotton Knit Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-8
          - pr-8
        justifyContent: flex-start
      subtitle:
        textAlign: center
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
