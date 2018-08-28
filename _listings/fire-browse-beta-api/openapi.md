---
swagger: "2.0"
x-collection-name: Fire Browse Beta API
x-complete: 1
info:
  title: Fire Browse Beta API
  description: a-simple-and-elegant-way-to-explore-cancer-data
  version: 1.1.35 (2016-09-27 10:12:23 6a47e74011281b2aa
host: firebrowse.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Metadata/TSSites:
    get:
      summary: Obtain identities of tissue source sites in TCGA.
      description: By default this function returns a table of all sites which contributed
        source tissue to TCGA, aka TSS's. A subset of this table may be obtained by
        explicitly specifying one or more sites.
      operationId: getMetadataTssites
      x-api-path-slug: metadatatssites-get
      parameters:
      - in: query
        name: format
        description: Format of result
      - in: query
        name: tss_code
        description: Narrow search to one or more TSS codes
      responses:
        200:
          description: OK
      tags:
      - Metadata
      - TSSites
---