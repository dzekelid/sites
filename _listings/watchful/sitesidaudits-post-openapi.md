---
swagger: "2.0"
x-collection-name: Watchful
x-complete: 0
info:
  title: Watchful Create An Audit For The Site
  description: Create an audit for the site
  version: 1.0.0
host: watchful.li
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /reports/sites/{id}:
    get:
      summary: Returns A PDF Report For A Specific Site
      description: Returns a PDF report based on a site ID
      operationId: reports.sites.id.get
      x-api-path-slug: reportssitesid-get
      parameters:
      - in: query
        name: compare
        description: Define if you want show previous values in Google Analytics graph
      - in: query
        name: from
        description: Start of the report, format YYYY-MM-DD, default today-30day
      - in: path
        name: id
        description: ID that needs to be fetched
      - in: query
        name: log_type
        description: Type of the log to show in the report
      - in: query
        name: reports
        description: 'Type of reports separate by comas: Ga,Logs,Uptime'
      - in: query
        name: to
        description: End of the report, format YYYY-MM-DD, default today
      responses:
        200:
          description: OK
      tags:
      - Reports
      - Sites
      - Id
  /sites:
    get:
      summary: Get A List Of Sites
      description: Returns a list of Sites
      operationId: getSites
      x-api-path-slug: sites-get
      parameters:
      - in: query
        name: access_url
        description: Access URL
      - in: query
        name: canUpdate
        description: canUpdate
      - in: query
        name: error
        description: Has errors
      - in: query
        name: fields
        description: Fields to return separated by commas (e
      - in: query
        name: ip
        description: Ip address
      - in: query
        name: jUpdate
        description: 'Joomla core update status (1: update required, 0: update not
          required)'
      - in: query
        name: j_version
        description: Joomla version
      - in: query
        name: limit
        description: Number of objects to return (max 100, default 25)
      - in: query
        name: limitstart
        description: Start of the return (default 0)
      - in: query
        name: name
        description: Site name
      - in: query
        name: nbUpdates
      - in: query
        name: order
        description: ORDER by this field separete by comas
      - in: query
        name: published
        description: Is published
      - in: query
        name: siteids
        description: List of sites id separated by comma
      - in: query
        name: up
        description: Is online
      responses:
        200:
          description: OK
      tags:
      - Sites
    post:
      summary: Create A Site
      description: Create a site
      operationId: createSite
      x-api-path-slug: sites-post
      parameters:
      - in: body
        name: body
        description: JSON object Site
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Sites
  /sites/metadata:
    get:
      summary: Get The List Of Fields
      description: Returns a list of fields
      operationId: sites.metadata.get
      x-api-path-slug: sitesmetadata-get
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Metadata
  /sites/{id}:
    delete:
      summary: Delete A Specific Site
      description: Delete a specific Site
      operationId: sites.id.delete
      x-api-path-slug: sitesid-delete
      parameters:
      - in: path
        name: id
        description: ID of Site that needs to be deleted
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Id
    get:
      summary: Find Sites By ID
      description: Return a site based on ID
      operationId: getSiteById
      x-api-path-slug: sitesid-get
      parameters:
      - in: query
        name: fields
        description: 'Fields to return separate by comas: name,id'
      - in: path
        name: id
        description: ID that needs to be fetched
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Id
    put:
      summary: Update A Site
      description: Update a site
      operationId: sites.id.put
      x-api-path-slug: sitesid-put
      parameters:
      - in: body
        name: body
        description: JSON object Site
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: ID of the website that needs to be update
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Id
  /sites/{id}/audits:
    get:
      summary: Return Audits For A Specific Website
      description: Return audits for a specific website
      operationId: getSiteAudits
      x-api-path-slug: sitesidaudits-get
      parameters:
      - in: query
        name: fields
        description: 'Fields to return separate by comas: name,id'
      - in: path
        name: id
        description: ID of the website
      - in: query
        name: limit
        description: Number of object to return (max 100, default 25)
      - in: query
        name: limitstart
        description: Start of the return (default 0)
      - in: query
        name: order
        description: ORDER by this field
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Id
      - Audits
    post:
      summary: Create An Audit For The Site
      description: Create an audit for the site
      operationId: createAudits
      x-api-path-slug: sitesidaudits-post
      parameters:
      - in: path
        name: id
        description: ID of the website
      responses:
        200:
          description: OK
      tags:
      - Sites
      - Id
      - Audits
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