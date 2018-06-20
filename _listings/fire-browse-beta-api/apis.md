---
name: Fire Browse Beta API
x-slug: fire-browse-beta-api
description: A simple and elegant way to explore cancer data. Sitting above one of
  the deepest and most integratively characterized open cancer datasets in the world.
  Backed by a powerful computational infrastructure, application programming interface
  (API), graphical tools and online reports. With over 80K sample aliquots from 11,000+
  cancer patients, spanning 38 unique disease cohorts.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Sites
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/fire-browse-beta-api/apis.md
specificationVersion: "0.14"
apis:
- name: Fire Browse Beta API Obtain identities of tissue source sites in TCGA.
  x-api-slug: fire-browse-beta-api
  description: By default this function returns a table of all sites which contributed
    source tissue to TCGA, aka TSS's. A subset of this table may be obtained by explicitly
    specifying one or more sites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1//Metadata/TSSites
  tags: Metadata,TSSites
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/fire-browse-beta-api/metadatatssites-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/fire-browse-beta-api/metadatatssites-get-openapi.md
- name: Fire Browse Beta API
  x-api-slug: fire-browse-beta-api
  description: A simple and elegant way to explore cancer data. Sitting above one
    of the deepest and most integratively characterized open cancer datasets in the
    world. Backed by a powerful computational infrastructure, application programming
    interface (API), graphical tools and online reports. With over 80K sample aliquots
    from 11,000+ cancer patients, spanning 38 unique disease cohorts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Sites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/fire-browse-beta-api/openapi.md
x-common:
- type: x-website
  url: http://firebrowse.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---