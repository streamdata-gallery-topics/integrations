---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Get the oauth url for the twitter integration service
  version: 1.0.0
  description: Get the oauth url for the twitter integration service.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/sync/googleanalyticsoauthurl/{brandId}/{personId}:
    get:
      summary: Get the oauth url for the google analytics integration service
      description: Get the oauth url for the google analytics integration service.
      operationId: Sync_GoogleAnalyticsOauthUrlBybrandIdBypersonId
      x-api-path-slug: apisyncgoogleanalyticsoauthurlbrandidpersonid-get
      parameters:
      - in: path
        name: brandId
      - in: path
        name: personId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Oauth
      - Urlthe
      - Google
      - Analytics
      - Integration
      - Service
  /api/twitter/oauthurl/{brandId}/{personId}:
    get:
      summary: Get the oauth url for the twitter integration service
      description: Get the oauth url for the twitter integration service.
      operationId: Twitter_TwitterOauthUrlBybrandIdBypersonId
      x-api-path-slug: apitwitteroauthurlbrandidpersonid-get
      parameters:
      - in: path
        name: brandId
      - in: path
        name: personId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Oauth
      - Urlthe
      - Twitter
      - Integration
      - Service
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