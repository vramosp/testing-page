---
title: This is a new page
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    variant: variant-a
    colors: colors-f
    width: wide
    height: tall
    bottomGap: none
    topGap: none
    contentWidth: large
    contentAlignHoriz: center
    contentAlignVert: middle
    textAlign: left
    title: This Is A Big Hero **Headline**
    text: >-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
        itae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions:
      - type: Button
        label: Get Started
        url: /
        style: primary
        elementId: hero-main-button
      - type: Button
        label: Learn More
        url: /
        style: secondary
      - elementId: ''
        label: Learn more
        altText: Learn more
        url: /
        showIcon: false
        icon: arrowLeft
        iconPosition: right
        style: secondary
        type: Button
    feature:
      type: ImageBlock
      url: /images/hero.png
      altText: Image alt text
  - elementId: ''
    colors: colors-a
    width: wide
    height: tall
    topGap: medium
    bottomGap: medium
    contentWidth: large
    contentAlignHoriz: left
    contentAlignVert: middle
    textAlign: center
    variant: variant-a
    badge: {}
    title: Latest news
    subtitle: Featured blog posts section example
    actions:
      - type: Button
        label: View all
        url: /
        style: primary
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    type: FeaturedPostsSection
layout: PageLayout
---
