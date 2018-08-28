---
swagger: "2.0"
x-collection-name: Atlassian
x-complete: 0
info:
  title: Jira Software Cloud API Get list of sites
  description: Authentication required, with scope participate:conversation
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/user:
    delete:
      summary: Delete user
      description: Deletes a user. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** Site administration (i.e., member of the site-admin [group](https://confluence.atlassian.com/display/Cloud/Manage+groups)).
      operationId: com.atlassian.jira.rest.v2.issue.UserResource.removeUser_delete
      x-api-path-slug: api2user-delete
      parameters:
      - in: query
        name: accountId
        description: the account ID
      - in: header
        name: force-account-id
      - in: query
        name: key
        description: The key of the user
      - in: query
        name: username
        description: The username of the user
      responses:
        200:
          description: OK
      tags:
      - User
  /site/:
    get:
      summary: Get list of sites
      description: Authentication required, with scope participate:conversation
      operationId: GetAllHandler
      x-api-path-slug: site-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
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