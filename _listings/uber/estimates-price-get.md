---
swagger: "2.0"
info:
  title: Uber Price Estimates
  description: The Price Estimates endpoint returns an estimated price range for each
    product offered at a given location. The price estimate is provided as a formatted
    string with the full price range and the localized currency symbol.<br><br>The
    response also includes low and high estimates, and the [ISO 4217](http://en.wikipedia.org/wiki/ISO_4217)
    currency code for situations requiring currency conversion. When surge is active
    for a particular product, its surge_multiplier will be greater than 1, but the
    price estimate already factors in this multiplier.
  version: 1.0.0
host: api.uber.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /estimates/price:
    get:
      summary: Price Estimates
      description: The Price Estimates endpoint returns an estimated price range for
        each product offered at a given location
      operationId: the-price-estimates-endpoint-returns-an-estimated-price-range-for-each-product-offered-at-a-given-lo
      parameters:
      - in: query
        name: end_latitude
        description: Latitude component of end location
      - in: query
        name: end_longitude
        description: Longitude component of end location
      - in: query
        name: start_latitude
        description: Latitude component of start location
      - in: query
        name: start_longitude
        description: Longitude component of start location
      responses:
        200:
          description: OK
      tags:
      - transportation
definitions:
  Product:
    properties:
      product_id:
        description: This is a default description.
        type: get
      description:
        description: This is a default description.
        type: get
      display_name:
        description: This is a default description.
        type: get
      capacity:
        description: This is a default description.
        type: get
      image:
        description: This is a default description.
        type: get
  ProductList:
    properties:
      products:
        description: This is a default description.
        type: get
  PriceEstimate:
    properties:
      product_id:
        description: This is a default description.
        type: get
      currency_code:
        description: This is a default description.
        type: get
      display_name:
        description: This is a default description.
        type: get
      estimate:
        description: This is a default description.
        type: get
      low_estimate:
        description: This is a default description.
        type: get
      high_estimate:
        description: This is a default description.
        type: get
      surge_multiplier:
        description: This is a default description.
        type: get
  Profile:
    properties:
      first_name:
        description: This is a default description.
        type: get
      last_name:
        description: This is a default description.
        type: get
      email:
        description: This is a default description.
        type: get
      picture:
        description: This is a default description.
        type: get
      promo_code:
        description: This is a default description.
        type: get
  Activity:
    properties:
      uuid:
        description: This is a default description.
        type: get
  Activities:
    properties:
      offset:
        description: This is a default description.
        type: get
      limit:
        description: This is a default description.
        type: get
      count:
        description: This is a default description.
        type: get
      history:
        description: This is a default description.
        type: get
  Error:
    properties:
      code:
        description: This is a default description.
        type: get
      message:
        description: This is a default description.
        type: get
      fields:
        description: This is a default description.
        type: get
x-collection-name: Uber
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---