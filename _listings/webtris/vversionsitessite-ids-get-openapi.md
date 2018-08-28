---
swagger: "2.0"
x-collection-name: WebTRIS
x-complete: 0
info:
  title: WebTRIS Traffic Flow API Get selected sites
  version: 1.0.0
  description: Get selected sites.
host: webtris.highwaysengland.co.uk
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v{version}/sites:
    get:
      summary: Get a list of sites
      description: Get a list of sites.
      operationId: Sites_Index
      x-api-path-slug: vversionsites-get
      parameters:
      - in: path
        name: version
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Sites
  /v{version}/sites/{site_Ids}:
    get:
      summary: Get selected sites
      description: Get selected sites.
      operationId: Sites_Index
      x-api-path-slug: vversionsitessite-ids-get
      parameters:
      - in: path
        name: site_Ids
        description: site id
      - in: path
        name: version
      responses:
        200:
          description: OK
      tags:
      - Selected
      - Sites
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