---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Create Site
  version: 1.0.0
  description: Inserts a new site.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/sites:
    get:
      summary: Get Sites
      description: Retrieves a list of sites, possibly filtered. This method supports
        paging.
      operationId: dfareporting.sites.list
      x-api-path-slug: userprofilesprofileidsites-get
      parameters:
      - in: query
        name: acceptsInStreamVideoPlacements
        description: This search filter is no longer supported and will have no effect
          on the results returned
      - in: query
        name: acceptsInterstitialPlacements
        description: This search filter is no longer supported and will have no effect
          on the results returned
      - in: query
        name: acceptsPublisherPaidPlacements
        description: Select only sites that accept publisher paid placements
      - in: query
        name: adWordsSite
        description: Select only AdWords sites
      - in: query
        name: approved
        description: Select only approved sites
      - in: query
        name: campaignIds
        description: Select only sites with these campaign IDs
      - in: query
        name: directorySiteIds
        description: Select only sites with these directory site IDs
      - in: query
        name: ids
        description: Select only sites with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for objects by name, ID or keyName
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      - in: query
        name: subaccountId
        description: Select only sites with this subaccount ID
      - in: query
        name: unmappedSite
        description: Select only sites that have not been mapped to a directory site
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Site
    patch:
      summary: Update Site
      description: Updates an existing site. This method supports patch semantics.
      operationId: dfareporting.sites.patch
      x-api-path-slug: userprofilesprofileidsites-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Site ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Site
    post:
      summary: Create Site
      description: Inserts a new site.
      operationId: dfareporting.sites.insert
      x-api-path-slug: userprofilesprofileidsites-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Site
    put:
      summary: Update Site
      description: Updates an existing site.
      operationId: dfareporting.sites.update
      x-api-path-slug: userprofilesprofileidsites-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Site
  /userprofiles/{profileId}/sites/{id}:
    get:
      summary: Get Site
      description: Gets one site by ID.
      operationId: dfareporting.sites.get
      x-api-path-slug: userprofilesprofileidsitesid-get
      parameters:
      - in: path
        name: id
        description: Site ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Site
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