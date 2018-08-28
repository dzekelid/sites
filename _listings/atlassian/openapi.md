swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
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