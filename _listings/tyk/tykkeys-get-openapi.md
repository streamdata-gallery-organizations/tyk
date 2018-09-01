---
swagger: "2.0"
x-collection-name: Tyk
x-complete: 0
info:
  title: Tyk API Management Get Keys
  description: Gets a list of *key* IDs (will only work with non-hashed installations)
  termsOfService: https://tyk.io/terms-and-conditions/
  version: "1.9"
host: '{baseURL}'
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tyk/keys/:
    get:
      summary: Get Keys
      description: Gets a list of *key* IDs (will only work with non-hashed installations)
      operationId: gets-a-list-of-key-ids-will-only-work-with-nonhashed-installations
      x-api-path-slug: tykkeys-get
      parameters:
      - in: query
        name: api_id
        description: Back-end to target
      - in: header
        name: x-tyk-authorization
        description: tyk gateway shared secret
      responses:
        200:
          description: OK
      tags:
      - API Key
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