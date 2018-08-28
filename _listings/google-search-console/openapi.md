swagger: "2.0"
x-collection-name: Google Search Console
x-complete: 1
info:
  title: Google Search Console URL Testing Tools
  description: provides-tools-for-running-validation-tests-against-single-urls
  contact:
    name: Google
    url: https://google.com
  version: v1
host: searchconsole.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /sites:
    get:
      summary: Get Sites
      description: Lists the user's Search Console sites.
      operationId: webmasters.sites.list
      x-api-path-slug: sites-get
      responses:
        200:
          description: OK
      tags:
      - Site
  /sites/{siteUrl}:
    delete:
      summary: Remove Site
      description: Removes a site from the set of the user's Search Console sites.
      operationId: webmasters.sites.delete
      x-api-path-slug: sitessiteurl-delete
      parameters:
      - in: path
        name: siteUrl
        description: The URI of the property as defined in Search Console
      responses:
        200:
          description: OK
      tags:
      - Site
    get:
      summary: Get Site
      description: Retrieves information about specific site.
      operationId: webmasters.sites.get
      x-api-path-slug: sitessiteurl-get
      parameters:
      - in: path
        name: siteUrl
        description: The URI of the property as defined in Search Console
      responses:
        200:
          description: OK
      tags:
      - Site
    put:
      summary: Update Site
      description: Adds a site to the set of the user's sites in Search Console.
      operationId: webmasters.sites.add
      x-api-path-slug: sitessiteurl-put
      parameters:
      - in: path
        name: siteUrl
        description: The URL of the site to add
      responses:
        200:
          description: OK
      tags:
      - Site
  /sites/{siteUrl}/sitemaps:
    get:
      summary: List Sitemap
      description: Lists the sitemaps-entries submitted for this site, or included
        in the sitemap index file (if sitemapIndex is specified in the request).
      operationId: webmasters.sitemaps.list
      x-api-path-slug: sitessiteurlsitemaps-get
      parameters:
      - in: query
        name: sitemapIndex
        description: A URL of a sites sitemap index
      - in: path
        name: siteUrl
        description: The sites URL, including protocol
      responses:
        200:
          description: OK
      tags:
      - Sitemap
  /sites/{siteUrl}/sitemaps/{feedpath}:
    delete:
      summary: Delete Sitemap
      description: Deletes a sitemap from this site.
      operationId: webmasters.sitemaps.delete
      x-api-path-slug: sitessiteurlsitemapsfeedpath-delete
      parameters:
      - in: path
        name: feedpath
        description: The URL of the actual sitemap
      - in: path
        name: siteUrl
        description: The sites URL, including protocol
      responses:
        200:
          description: OK
      tags:
      - Sitemap
    get:
      summary: Get Sitemap
      description: Retrieves information about a specific sitemap.
      operationId: webmasters.sitemaps.get
      x-api-path-slug: sitessiteurlsitemapsfeedpath-get
      parameters:
      - in: path
        name: feedpath
        description: The URL of the actual sitemap
      - in: path
        name: siteUrl
        description: The sites URL, including protocol
      responses:
        200:
          description: OK
      tags:
      - Sitemap
    put:
      summary: Update Sitemap
      description: Submits a sitemap for a site.
      operationId: webmasters.sitemaps.submit
      x-api-path-slug: sitessiteurlsitemapsfeedpath-put
      parameters:
      - in: path
        name: feedpath
        description: The URL of the sitemap to add
      - in: path
        name: siteUrl
        description: The sites URL, including protocol
      responses:
        200:
          description: OK
      tags:
      - Sitemap