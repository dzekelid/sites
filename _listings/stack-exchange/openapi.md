---
swagger: "2.0"
x-collection-name: Stack Exchange
x-complete: 1
info:
  title: Stack Exchange
  description: stack-exchange-is-a-network-of-130-qa-communities-including-stack-overflow-
  version: "2.0"
host: api.stackexchange.com
basePath: /2.2
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
      description: "Returns all sites in the network.\n \nThis method allows for discovery
        of new sites, and changes to existing ones. Be aware that unlike normal API
        methods, this method should be fetched very infrequently, it is very unusual
        for these values to change more than once on any given day. It is suggested
        that you cache its return for at least one day, unless your app encounters
        evidence that it has changed (such as from the /info method).\n \nThe pagesize
        parameter for this method is unbounded, in acknowledgement that for many applications
        repeatedly fetching from /sites would complicate start-up tasks needlessly.\n
        \nThis method returns a list of sites."
      operationId: returns-all-sites-in-the-network-this-method-allows-for-discovery-of-new-sites-and-changes-to-existi
      x-api-path-slug: sites-get
      parameters:
      - in: query
        name: callback
        description: All API responses are JSON, we do support JSONP with the callback
          query parameter
      - in: query
        name: filter
        description: '#DiscussionThe Stack Exchange API allows applications to exclude
          almost every field returned'
      - in: query
        name: page
      - in: query
        name: pagesize
      responses:
        200:
          description: OK
      tags:
      - Sites
---