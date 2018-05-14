---
name: Uber
description: The Uber API exposes a set of RESTful endpoints that enable your application
  to GET information such as time and price estimates about the products offered in
  a given location, request rides on behalf of authenticated users, and create ride
  reminders for users to take a ride at a specific time in the future.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/uber-logo.png
x-kinRank: "9"
x-alexaRank: ""
tags:
- Transportation
- Transport
- Taxi
- Stack Network
- Stack
- Cars
- Autos
- Automobile
- API LIfeycle
created: "2018-03-24"
modified: "2018-03-24"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/transportation/master/_listings/uber/apis.yaml
specificationVersion: "0.14"
apis:
- name: Uber
  description: The Uber API exposes a set of RESTful endpoints that enable your application
    to GET information such as time and price estimates about the products offered
    in a given location, request rides on behalf of authenticated users, and create
    ride reminders for users to take a ride at a specific time in the future
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/uber-logo.png
  humanURL: ""
  baseURL: https://api.uber.com//v1
  tags: Transportation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/transportation/master/_listings/uber/history-get.md
- name: Uber Price Estimates
  description: The Price Estimates endpoint returns an estimated price range for each
    product offered at a given location. The price estimate is provided as a formatted
    string with the full price range and the localized currency symbol.<br><br>The
    response also includes low and high estimates, and the [ISO 4217](http://en.wikipedia.org/wiki/ISO_4217)
    currency code for situations requiring currency conversion. When surge is active
    for a particular product, its surge_multiplier will be greater than 1, but the
    price estimate already factors in this multiplier.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/uber-logo.png
  humanURL: https://uber.com
  baseURL: https://api.uber.com//v1
  tags: Transportation
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/transportation/master/_listings/uber/estimates-price-get.md
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/transportation/master/_listings/uber/estimates-price-get-postman.md
x-common:
- type: x-apijson--authoritative
  url: https://raw.githubusercontent.com/picsoung/apis.json/master/uber.json
- type: x-blog
  url: https://medium.com/@UberPubPolicy
- type: x-blog
  url: https://devblog.uber.com/
- type: x-blog-rss
  url: https://medium.com/feed/@UberPubPolicy
- type: x-blog-rss
  url: https://devblog.uber.com/feed/
- type: x-developer
  url: https://developer.uber.com/
- type: x-github
  url: https://github.com/uber
- type: x-transparency-report
  url: https://transparencyreport.uber.com/
- type: x-twitter
  url: https://twitter.com/uber_api
- type: x-twitter
  url: https://twitter.com/UberPubPolicy
- type: x-website
  url: https://uber.com
- type: x-apijson--authoritative
  url: https://raw.githubusercontent.com/picsoung/apis.json/master/uber.json
- type: x-blog
  url: https://medium.com/@UberPubPolicy
- type: x-blog
  url: https://devblog.uber.com/
- type: x-blog-rss
  url: https://medium.com/feed/@UberPubPolicy
- type: x-blog-rss
  url: https://devblog.uber.com/feed/
- type: x-developer
  url: https://developer.uber.com/
- type: x-github
  url: https://github.com/uber
- type: x-transparency-report
  url: https://transparencyreport.uber.com/
- type: x-twitter
  url: https://twitter.com/uber_api
- type: x-twitter
  url: https://twitter.com/UberPubPolicy
- type: x-website
  url: https://uber.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---