---
name: Lyft
description: Lyft is a peer-to-peer transportation platform that connects passengers
  who need rides with drivers willing to provide rides using their own personal vehicles.
  Lyft was started in 2012 with the mission of building a peer-to-peer transportation
  solution that would help make cities safer, more affordable and better connected.
  Lyft now operates in 68 cities across the U.S.n
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/lyft-logo.png
x-kinRank: "8"
x-alexaRank: ""
tags:
- Transportation
- Stack Network
- Stack
- Imports
created: "2018-03-24"
modified: "2018-03-24"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/transportation/master/_listings/lyft/apis.yaml
specificationVersion: "0.14"
apis:
- name: Lyft
  description: Lyft is a peer-to-peer transportation platform that connects passengers
    who need rides with drivers willing to provide rides using their own personal
    vehicles
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/lyft-logo.png
  humanURL: ""
  baseURL: https://api.lyft.com//v1
  tags: Transportation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/transportation/master/_listings/lyft/sandbox-ridetypes-ride-type-put.md
- name: Lyft Request a Lyft
  description: Request a Lyft come pick you up at the given location.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/lyft-logo.png
  humanURL: https://www.lyft.com/
  baseURL: https://api.lyft.com//v1
  tags: Transportation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/transportation/master/_listings/lyft/rides-post.md
- name: Lyft Add the passenger's rating, feedback, and tip
  description: Add the passenger's 1 to 5 star rating of the ride, optional written
    feedback, and optional tip amount in minor units and currency. The ride must already
    be dropped off, and ratings must be given within 24 hours of drop off. For purposes
    of display, 5 is considered the default rating. When this endpoint is successfully
    called, payment processing will begin.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/lyft-logo.png
  humanURL: https://www.lyft.com/
  baseURL: https://api.lyft.com//v1
  tags: Transportation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/transportation/master/_listings/lyft/rides-id-rating-put.md
x-common:
- type: x-authentication
  url: https://developer.lyft.com/docs/authentication
- type: x-blog
  url: http://blog.lyft.com/
- type: x-blog-rss
  url: http://blog.lyft.com/posts?format=RSS
- type: x-branding
  url: https://developer.lyft.com/docs/brand-guidelines
- type: x-developer
  url: https://www.lyft.com/developers
- type: x-documentation
  url: http://petstore.swagger.io/?url=https://api.lyft.com/v1/spec
- type: x-github
  url: https://github.com/lyft
- type: x-manage-applications
  url: https://www.lyft.com/developers/manage
- type: x-openapi-spec
  url: https://api.lyft.com/v1/spec
- type: x-partners
  url: https://www.lyft.com/partnerships
- type: x-rate-limits
  url: https://developer.lyft.com/docs/rate-limits
- type: x-twitter
  url: https://twitter.com/lyft
- type: x-website
  url: https://www.lyft.com/
- type: x-authentication
  url: https://developer.lyft.com/docs/authentication
- type: x-blog
  url: http://blog.lyft.com/
- type: x-blog-rss
  url: http://blog.lyft.com/posts?format=RSS
- type: x-branding
  url: https://developer.lyft.com/docs/brand-guidelines
- type: x-developer
  url: https://www.lyft.com/developers
- type: x-documentation
  url: http://petstore.swagger.io/?url=https://api.lyft.com/v1/spec
- type: x-github
  url: https://github.com/lyft
- type: x-manage-applications
  url: https://www.lyft.com/developers/manage
- type: x-openapi-spec
  url: https://api.lyft.com/v1/spec
- type: x-partners
  url: https://www.lyft.com/partnerships
- type: x-rate-limits
  url: https://developer.lyft.com/docs/rate-limits
- type: x-twitter
  url: https://twitter.com/lyft
- type: x-website
  url: https://www.lyft.com/
- type: x-authentication
  url: https://developer.lyft.com/docs/authentication
- type: x-blog
  url: http://blog.lyft.com/
- type: x-blog-rss
  url: http://blog.lyft.com/posts?format=RSS
- type: x-branding
  url: https://developer.lyft.com/docs/brand-guidelines
- type: x-developer
  url: https://www.lyft.com/developers
- type: x-documentation
  url: http://petstore.swagger.io/?url=https://api.lyft.com/v1/spec
- type: x-github
  url: https://github.com/lyft
- type: x-manage-applications
  url: https://www.lyft.com/developers/manage
- type: x-openapi-spec
  url: https://api.lyft.com/v1/spec
- type: x-partners
  url: https://www.lyft.com/partnerships
- type: x-rate-limits
  url: https://developer.lyft.com/docs/rate-limits
- type: x-twitter
  url: https://twitter.com/lyft
- type: x-website
  url: https://www.lyft.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---