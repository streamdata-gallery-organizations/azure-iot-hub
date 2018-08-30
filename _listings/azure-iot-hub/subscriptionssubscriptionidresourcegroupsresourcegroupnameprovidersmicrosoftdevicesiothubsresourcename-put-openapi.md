---
swagger: "2.0"
x-collection-name: Azure IoT Hub
x-complete: 0
info:
  title: Azure IoT Hub API Iot Hub Resource Create Or Update
  description: Create or update the metadata of an Iot hub. The usual pattern to modify
    a property is to retrieve the IoT hub metadata and security metadata, and then
    combine them with the modified values in a new body to update the IoT hub.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}:
    get:
      summary: Iot Hub Resource Get
      description: Get the non-security related metadata of an IoT hub.
      operationId: IotHubResource_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevicesiothubsresourcename-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the IoT hub
      - in: path
        name: resourceName
        description: The name of the IoT hub
      responses:
        200:
          description: OK
      tags:
      - Iot Hub Resource
    put:
      summary: Iot Hub Resource Create Or Update
      description: Create or update the metadata of an Iot hub. The usual pattern
        to modify a property is to retrieve the IoT hub metadata and security metadata,
        and then combine them with the modified values in a new body to update the
        IoT hub.
      operationId: IotHubResource_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevicesiothubsresourcename-put
      parameters:
      - in: body
        name: iotHubDescription
        description: The IoT hub metadata and security metadata
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the IoT hub
      - in: path
        name: resourceName
        description: The name of the IoT hub to create or update
      responses:
        200:
          description: OK
      tags:
      - Iot Hub Resource
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---