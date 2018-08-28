---
name: Google Search Console
x-slug: google-search-console
description: Search Console is a free service that enables you to monitor your sites
  performance in Google Search, to ensure that Google can crawl your site or app correctly,
  and to test the validity and performance of a given page. Search Console provides
  programmatic access to the service through the APIs documented here.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
x-kinRank: "9"
x-alexaRank: "0"
tags: Sites
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/apis.md
specificationVersion: "0.14"
apis:
- name: Search Console - Get Sites
  x-api-slug: sites-get
  description: Lists the user's Search Console sites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sites-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sites-get-openapi.md
- name: Search Console - Remove Site
  x-api-slug: sitessiteurl-delete
  description: Removes a site from the set of the user's Search Console sites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-delete-openapi.md
- name: Search Console - Get Site
  x-api-slug: sitessiteurl-get
  description: Retrieves information about specific site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-get-openapi.md
- name: Search Console - Update Site
  x-api-slug: sitessiteurl-put
  description: Adds a site to the set of the user's sites in Search Console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-put-openapi.md
- name: Search Console - List Sitemap
  x-api-slug: sitessiteurlsitemaps-get
  description: Lists the sitemaps-entries submitted for this site, or included in
    the sitemap index file (if sitemapIndex is specified in the request).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemaps-get-openapi.md
- name: Search Console - Delete Sitemap
  x-api-slug: sitessiteurlsitemapsfeedpath-delete
  description: Deletes a sitemap from this site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemapsfeedpath-delete-openapi.md
- name: Search Console - Get Sitemap
  x-api-slug: sitessiteurlsitemapsfeedpath-get
  description: Retrieves information about a specific sitemap.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemapsfeedpath-get-openapi.md
- name: Search Console - Update Sitemap
  x-api-slug: sitessiteurlsitemapsfeedpath-put
  description: Submits a sitemap for a site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemapsfeedpath-put-openapi.md
- name: Search Console - Get Sites
  x-api-slug: sites-get
  description: Lists the user's Search Console sites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sites-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sites-get-openapi.md
- name: Search Console - Remove Site
  x-api-slug: sitessiteurl-delete
  description: Removes a site from the set of the user's Search Console sites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-delete-openapi.md
- name: Search Console - Get Site
  x-api-slug: sitessiteurl-get
  description: Retrieves information about specific site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-get-openapi.md
- name: Search Console - Update Site
  x-api-slug: sitessiteurl-put
  description: Adds a site to the set of the user's sites in Search Console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-put-openapi.md
- name: Search Console - List Sitemap
  x-api-slug: sitessiteurlsitemaps-get
  description: Lists the sitemaps-entries submitted for this site, or included in
    the sitemap index file (if sitemapIndex is specified in the request).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemaps-get-openapi.md
- name: Search Console - Delete Sitemap
  x-api-slug: sitessiteurlsitemapsfeedpath-delete
  description: Deletes a sitemap from this site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemapsfeedpath-delete-openapi.md
- name: Search Console - Get Sitemap
  x-api-slug: sitessiteurlsitemapsfeedpath-get
  description: Retrieves information about a specific sitemap.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemapsfeedpath-get-openapi.md
- name: Search Console - Update Sitemap
  x-api-slug: sitessiteurlsitemapsfeedpath-put
  description: Submits a sitemap for a site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemapsfeedpath-put-openapi.md
- name: Search Console - Update Site
  x-api-slug: sitessiteurl-put
  description: Adds a site to the set of the user's sites in Search Console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-put-openapi.md
- name: Search Console - Get Site
  x-api-slug: sitessiteurl-get
  description: Retrieves information about specific site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-get-openapi.md
- name: Search Console - Remove Site
  x-api-slug: sitessiteurl-delete
  description: Removes a site from the set of the user's Search Console sites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurl-delete-openapi.md
- name: Search Console - Get Sites
  x-api-slug: sites-get
  description: Lists the user's Search Console sites.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sites-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sites-get-openapi.md
- name: Search Console - Update Sitemap
  x-api-slug: sitessiteurlsitemapsfeedpath-put
  description: Submits a sitemap for a site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemapsfeedpath-put-openapi.md
- name: Search Console - Get Sitemap
  x-api-slug: sitessiteurlsitemapsfeedpath-get
  description: Retrieves information about a specific sitemap.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemapsfeedpath-get-openapi.md
- name: Search Console - Delete Sitemap
  x-api-slug: sitessiteurlsitemapsfeedpath-delete
  description: Deletes a sitemap from this site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemapsfeedpath-delete-openapi.md
- name: Search Console - List Sitemap
  x-api-slug: sitessiteurlsitemaps-get
  description: Lists the sitemaps-entries submitted for this site, or included in
    the sitemap index file (if sitemapIndex is specified in the request).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/subdomains-google-webmaster-tools-13960.gif
  humanURL: https://developers.google.com/webmaster-tools/
  baseURL: ://www.googleapis.com//webmasters/v3
  tags: Google APIs, Search, Links, Stack Network, API Service Provider, API Provider,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/sites/master/_listings/google-search-console/sitessiteurlsitemaps-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.safe.browsing.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.search.console.stack.network
- type: x-blog
  url: https://support.google.com/webmasters/go/blog
- type: x-blog-rss
  url: https://webmasters.googleblog.com/feeds/posts/default?alt=rss
- type: x-forum
  url: https://productforums.google.com/forum/#!forum/webmasters
- type: x-website
  url: https://developers.google.com/webmaster-tools/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---