---
name: Watchful
x-slug: watchful
description: Watchful resulted from the need for a single, unified dashboard to easily
  monitor all of the web sites in our portfolios. After years of evolution, our solution
  has matured into a simple, complete and professional service.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
x-kinRank: "8"
x-alexaRank: "0"
tags: Sites
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/apis.md
specificationVersion: "0.14"
apis:
- name: Watchful Returns A PDF Report For A Specific Site
  x-api-slug: watchful
  description: Returns a PDF report based on a site ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//reports/sites/{id}
  tags: Reports,Sites,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/reportssitesid-get-openapi.md
- name: Watchful Get A List Of Sites
  x-api-slug: watchful
  description: Returns a list of Sites
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites
  tags: Sites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sites-get-openapi.md
- name: Watchful Create A Site
  x-api-slug: watchful
  description: Create a site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites
  tags: Sites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sites-post-openapi.md
- name: Watchful Get The List Of Fields
  x-api-slug: watchful
  description: Returns a list of fields
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/metadata
  tags: Sites,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesmetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesmetadata-get-openapi.md
- name: Watchful Delete A Specific Site
  x-api-slug: watchful
  description: Delete a specific Site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}
  tags: Sites,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesid-delete-openapi.md
- name: Watchful Find Sites By ID
  x-api-slug: watchful
  description: Return a site based on ID
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}
  tags: Sites,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesid-get-openapi.md
- name: Watchful Update A Site
  x-api-slug: watchful
  description: Update a site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}
  tags: Sites,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesid-put-openapi.md
- name: Watchful Return Audits For A Specific Website
  x-api-slug: watchful
  description: Return audits for a specific website
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/audits
  tags: Sites,Id,Audits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidaudits-get-openapi.md
- name: Watchful Create An Audit For The Site
  x-api-slug: watchful
  description: Create an audit for the site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/audits
  tags: Sites,Id,Audits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidaudits-post-openapi.md
- name: Watchful Add The Site To The Backup Queue
  x-api-slug: watchful
  description: Add the site to the backup queue
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/backupnow
  tags: Sites,Id,Backupnow
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidbackupnow-post-openapi.md
- name: Watchful Return Backup Profile
  x-api-slug: watchful
  description: Return backup profile
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/backupprofiles
  tags: Sites,Id,Backupprofiles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidbackupprofiles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidbackupprofiles-get-openapi.md
- name: Watchful List Of Latest Backups
  x-api-slug: watchful
  description: List of latest backups
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/backups
  tags: Sites,Id,Backups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidbackups-get-openapi.md
- name: Watchful Start A Remote Backup For The Site
  x-api-slug: watchful
  description: Start a remote backup for the site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/backupstart
  tags: Sites,Id,Backupstart
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidbackupstart-post-openapi.md
- name: Watchful Step (continue) A Remote Backup For The Site
  x-api-slug: watchful
  description: Step (continue) a remote backup for the site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/backupstep
  tags: Sites,Id,Backupstep
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidbackupstep-post-openapi.md
- name: Watchful Get Extensions For A Site
  x-api-slug: watchful
  description: Get extensions for a site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/extensions
  tags: Sites,Id,Extensions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidextensions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidextensions-get-openapi.md
- name: Watchful Install Extension
  x-api-slug: watchful
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/extensions
  tags: Sites,Id,Extensions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidextensions-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidextensions-post-openapi.md
- name: Watchful Return Logs For A Specific Website
  x-api-slug: watchful
  description: Return logs for a specific website
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/logs
  tags: Sites,Id,Logs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidlogs-get-openapi.md
- name: Watchful Create A Custom Log For A Specific Website
  x-api-slug: watchful
  description: Create a custom log for a specific website
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/logs
  tags: Sites,Id,Logs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidlogs-post-openapi.md
- name: Watchful Delete Uptime Monitor
  x-api-slug: watchful
  description: Return boolean
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/monitor
  tags: Sites,Id,Monitor
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidmonitor-delete-openapi.md
- name: Watchful Post Uptime Monitor
  x-api-slug: watchful
  description: Return boolean
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/monitor
  tags: Sites,Id,Monitor
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidmonitor-post-openapi.md
- name: Watchful Scan The Site For Malware
  x-api-slug: watchful
  description: Scan the site for malware
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/scanner
  tags: Sites,Id,Scanner
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidscanner-get-openapi.md
- name: Watchful SEO Analyze For A Page
  x-api-slug: watchful
  description: SEO analyze for a page
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/seo
  tags: Sites,Id,Seo
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidseo-get-openapi.md
- name: Watchful Return Tags For A Specific Website
  x-api-slug: watchful
  description: Return tags for a specific website
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/tags
  tags: Sites,Id,Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidtags-get-openapi.md
- name: Watchful Add Tags For A Specific Website
  x-api-slug: watchful
  description: Add tags for a specific website
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/tags
  tags: Sites,Id,Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidtags-post-openapi.md
- name: Watchful Update Joomla Core On The Remote Site
  x-api-slug: watchful
  description: Update Joomla core on the remote site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/updatejoomla
  tags: Sites,Id,Updatejoomla
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidupdatejoomla-post-openapi.md
- name: Watchful Return Uptime Data
  x-api-slug: watchful
  description: Return uptime data
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/uptime
  tags: Sites,Id,Uptime
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesiduptime-get-openapi.md
- name: Watchful Validate The Site, Return The New Logs
  x-api-slug: watchful
  description: validate the site
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/validate
  tags: Sites,Id,Validate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidvalidate-get-openapi.md
- name: Watchful Validate The Site, Return The Debug Information
  x-api-slug: watchful
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//sites/{id}/validatedebug
  tags: Sites,Id,Validatedebug
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/sitesidvalidatedebug-get-openapi.md
- name: Watchful Find Sites By Tag ID
  x-api-slug: watchful
  description: Returns a list of sites based with a specific tag id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1//tags/{id}/sites
  tags: Tags,Id,Sites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/tagsidsites-get-openapi.md
- name: Watchful
  x-api-slug: watchful
  description: Watchful resulted from the need for a single, unified dashboard to
    easily monitor all of the web sites in our portfolios. After years of evolution,
    our solution has matured into a simple, complete and professional service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/watchful-li-logo.jpg
  humanURL: http://watchful.li
  baseURL: https://watchful.li//api/v1
  tags: Sites
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/watchful/openapi.md
x-common:
- type: x-application-gallery
  url: https://watchful.li/apps/
- type: x-blog
  url: https://watchful.li/news/
- type: x-blog-rss
  url: https://watchful.li/news/feed/rss.html
- type: x-developer
  url: https://watchful.li/support-services/kb/article/watchful-rest-api
- type: x-facebook
  url: https://www.facebook.com/watchfulli
- type: x-faq
  url: https://watchful.li/support-services/faq.html
- type: x-google-plus
  url: https://plus.google.com/+WatchfulLi
- type: x-knowledgebase
  url: https://watchful.li/support-services/kb.html
- type: x-pricing
  url: https://watchful.li/pricing
- type: x-privacy
  url: https://watchful.li/privacy-policy.html
- type: x-terms-of-service
  url: https://watchful.li/terms-of-service.html
- type: x-twitter
  url: https://twitter.com/watchfulli
- type: x-website
  url: http://watchful.li
- type: x-website
  url: https://watchful.li/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---