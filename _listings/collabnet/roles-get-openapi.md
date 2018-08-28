---
swagger: "2.0"
x-collection-name: CollabNet
x-complete: 0
info:
  title: CollabNet TeamForge API Documentation Gets global/site role list
  version: 1.0.0
  description: Gets global/site role list.
basePath: /ctfrest/foundation/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /roles:
    get:
      summary: Gets global/site role list
      description: Gets global/site role list.
      operationId: getRoles
      x-api-path-slug: roles-get
      parameters:
      - in: query
        name: projectId
        description: Context project id (to verify access permissions)
      - in: query
        name: type
        description: Role type
      responses:
        200:
          description: OK
      tags:
      - Global
      - Site
      - Role
      - List
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