{
  "info": {
    "name": "Azure IoT Hub API Iot Hub Resource List Event Hub Consumer Groups",
    "_postman_id": "b61b9140-fd2a-4003-9ecb-7615cbb594c1",
    "description": "Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "iot hub resource event hub consumer groups",
      "item": [
        {
          "id": "1b21750f-68db-4f26-af59-941aba29c01d",
          "name": "IotHubResource_ListEventHubConsumerGroups",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Devices/IotHubs/:resourceName/eventHubEndpoints/:eventHubEndpointName/ConsumerGroups"
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
                  "id": "eventHubEndpointName",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Get a list of the consumer groups in the Event Hub-compatible device-to-cloud endpoint in an IoT hub"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "92c966e2-680a-4977-985f-ab725901a392"
            }
          ]
        }
      ]
    }
  ]
}