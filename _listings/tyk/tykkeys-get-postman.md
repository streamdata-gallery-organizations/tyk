{
  "info": {
    "name": "Tyk API Management Get Keys",
    "_postman_id": "de660593-9dc6-4f6d-bd27-2ea6b7d9ff89",
    "description": "Gets a list of *key* IDs (will only work with non-hashed installations)",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "API Key",
      "item": [
        {
          "id": "1767b999-4def-4786-80b7-d5f84e7322a1",
          "name": "gets-a-list-of-key-ids-will-only-work-with-nonhashed-installations",
          "request": {
            "url": "http://TODO Add Value for parameter.../tyk/keys/?api_id=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "x-tyk-authorization",
                "value": "{}",
                "description": "tyk gateway shared secret",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a list of *key* IDs (will only work with non-hashed installations)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a880c80-617e-4bc4-8a4e-f898b7404d3f"
            }
          ]
        }
      ]
    }
  ]
}