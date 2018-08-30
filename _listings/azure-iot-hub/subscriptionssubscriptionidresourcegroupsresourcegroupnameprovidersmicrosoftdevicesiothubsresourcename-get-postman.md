{
  "info": {
    "name": "Azure IoT Hub API Iot Hub Resource Get",
    "_postman_id": "eee3e3a5-ca81-4a60-a777-bd273b04ae9a",
    "description": "Get the non-security related metadata of an IoT hub.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Iot Hub Resource",
      "item": [
        {
          "id": "f0453ec9-c5c6-4b55-a9b2-26ad5e0ed113",
          "name": "IotHubResource_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Devices/IotHubs/:resourceName"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "resourceGroupName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "resourceName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get the non-security related metadata of an IoT hub."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6f99346-98e2-4cf9-8c05-367e0c54f531"
            }
          ]
        }
      ]
    }
  ]
}