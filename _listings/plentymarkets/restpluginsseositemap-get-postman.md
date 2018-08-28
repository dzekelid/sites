{
  "info": {
    "name": "Plentymarkets Load sitemap patterns",
    "_postman_id": "d5cedfb8-08c0-4c26-8794-e9e36e8e3803",
    "description": "Loads all given sitemap patterns from booted plugins.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Load",
      "item": [
        {
          "id": "45807cb2-f1de-4ea2-9144-eec8ff86f119",
          "name": "getRestPluginsSeoSitemap",
          "request": {
            "url": "http://example.com/rest/plugins/seo/sitemap",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Loads all given sitemap patterns from booted plugins."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ace554a-73b1-45c2-afc4-128d83cac3a8"
            }
          ]
        }
      ]
    }
  ]
}