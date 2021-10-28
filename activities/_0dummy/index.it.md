---
template: activities-single
slug: /_dummy
hidden: true
draft: true
priority: 1
homepage: false
seo:
  title: SEO title (falls back to `title`)
  description: SEO description (falls back to `subtitle`)
  ogimage: ./cover.jpg
title: Entry title
subtitle: Entry subtitle
startYear: 2020
cover:
  image: ./cover.jpg
  caption: A cover image caption
categories:
  - activities
  - blog
  - events
  - news
  - projects
partners:
  - amici-de-laschola
people:
  - beatrice
showUpcomingEvents: false
hasInitial: false
columned: false
schedules:
  - id: schedule-id
    groups:
    - id: group-name
      title: Group name
    activities:
    - id: activity-unique-slug
      desc: Activity description
    periods:
    - datetime: 2020-07-30
      activities:
      - from: '15:00'
        to: '16:00'
        group: group-name
        text: Description of the activity
      - time: 'morning'
        group: group-name
        id: activity-unique-slug
gallery:
  title: Galleria immagini
  items:
    - image: ./cover.jpg
      alt: ''
---

A dummy entry to safely infer the frontmatter Graphql types
