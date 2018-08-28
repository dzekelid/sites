swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/plugins/seo/sitemap:
    get:
      summary: Load sitemap patterns
      description: Loads all given sitemap patterns from booted plugins.
      operationId: getRestPluginsSeoSitemap
      x-api-path-slug: restpluginsseositemap-get
      responses:
        200:
          description: OK
      tags:
      - Load
      - Sitemap
      - Patterns