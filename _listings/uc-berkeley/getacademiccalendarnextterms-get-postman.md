{
  "info": {
    "name": "UC Berkeley Academic Terms API Next Academic Terms",
    "_postman_id": "e89a96a7-855e-4409-950b-4324555ee3c3",
    "description": "Get a list of academic terms for the coming year.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Next",
      "item": [
        {
          "id": "e639c516-cc21-42ff-b55e-5fc505b5b4b2",
          "name": "getGetacademiccalendarnextterms",
          "request": {
            "url": "http://apis.berkeley.edu/sisconnect/GetAcademicCalendarNextTerms",
            "method": "GET",
            "header": [
              {
                "key": "app_id",
                "value": "{}",
                "description": "App ID",
                "disabled": false
              },
              {
                "key": "app_key",
                "value": "{}",
                "description": "App Key",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get a list of academic terms for the coming year."
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "bf653bd9-1294-430a-b91a-18bc08000226"
            }
          ]
        }
      ]
    }
  ]
}