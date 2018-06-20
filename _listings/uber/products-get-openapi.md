---
swagger: "2.0"
x-collection-name: Uber
x-complete: 0
info:
  title: Uber Product Types
  description: The Products endpoint returns information about the Uber products offered
    at a given location. The response includes the display name and other details
    about each product, and lists the products in the proper display order.
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
  /products:
    get:
      summary: Product Types
      description: The Products endpoint returns information about the Uber products
        offered at a given location. The response includes the display name and other
        details about each product, and lists the products in the proper display order.
      operationId: the-products-endpoint-returns-information-about-the-uber-products-offered-at-a-given-location-the-re
      x-api-path-slug: products-get
      parameters:
      - in: query
        name: latitude
        description: Latitude component of location
      - in: query
        name: longitude
        description: Longitude component of location
      responses:
        1:
          description: User not found
        100:
          description: Invalid API Key - The API key passed was not valid or has expired
        105:
          description: Service currently unavailable - The requested service is temporarily
            unavailable
        106:
          description: Write operation failed - The requested operation failed due
            to a temporary issue
        111:
          description: Format "xxx" not found - The requested response format was
            not found
        112:
          description: Method "xxx" not found - The requested method was not found
        114:
          description: Invalid SOAP envelope - The SOAP envelope send in the request
            could not be parsed
        115:
          description: Invalid XML-RPC Method Call - The XML-RPC request document
            could not be parsed
        116:
          description: Bad URL found - One or more arguments contained a URL that
            has been used for abuse on Flickr
        200:
          description: OK
      tags:
      - Transportation
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