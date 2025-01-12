---
type: PageLayout
title: Home
colors: colors-a
sections:
  - type: FeaturedPostsSection
    title: 'Posts:'
    actions:
      - type: Link
        label: See all posts
        altText: See all posts
        url: /blog
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    posts:
      - content/pages/blog/post-five.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    colors: colors-d
    variant: variant-d
    elementId: ''
    showDate: true
    showAuthor: false
    showExcerpt: true
    showFeaturedImage: false
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
backgroundImage:
  type: BackgroundImage
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 100
  url: /images/featured-Image2.jpg
---
