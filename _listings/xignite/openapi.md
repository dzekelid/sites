---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Bonds
  description: xignitebonds-service-provides-fourhour-delayed-price-data-for-us-corporate-and-agency-debt-bonds-including-debt-securities-issued-by-governmentsponsored-enterprises-gse--price-data-includes-last-sale-yield-daily-and-yearly-open-high-low-close-trade-price-data-
  version: 1.0.0
host: bonds.xignite.com
basePath: xBonds.json/XigniteBonds
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetPriceComposites:
    get:
      summary: Get Price Composites
      description: Returns price data composite including last sale price, yield and
        daily and yearly Open, High, Low prices for the list of bonds specified in
        the input. Each PriceComposite object returned in the output counts as three
        hits.
      operationId: GetPriceComposites
      x-api-path-slug: getpricecomposites-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Price
      - Composites
---