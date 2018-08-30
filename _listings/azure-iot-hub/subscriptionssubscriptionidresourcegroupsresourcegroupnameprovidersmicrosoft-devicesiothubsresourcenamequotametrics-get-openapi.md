---
swagger: "2.0"
x-collection-name: Azure IoT Hub
x-complete: 0
info:
  title: Azure IoT Hub API Iot Hub Resource Get Quota Metrics
  description: Get the quota metrics for an IoT hub.
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-put
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
    delete:
      summary: Iot Hub Resource Delete
      description: Delete an IoT hub.
      operationId: IotHubResource_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the IoT hub
      - in: path
        name: resourceName
        description: The name of the IoT hub to delete
      responses:
        200:
          description: OK
      tags:
      - Iot Hub Resource
  /subscriptions/{subscriptionId}/providers/Microsoft.Devices/IotHubs:
    get:
      summary: Iot Hub Resource List By Subscription
      description: Get all the IoT hubs in a subscription.
      operationId: IotHubResource_ListBySubscription
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-devicesiothubs-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Iot Hub Resource Subscription
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs:
    get:
      summary: Iot Hub Resource List By Resource Group
      description: Get all the IoT hubs in a resource group.
      operationId: IotHubResource_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubs-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains the IoT hubs
      responses:
        200:
          description: OK
      tags:
      - Iot Hub Resource Resource Group
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/IotHubStats
  : get:
      summary: Iot Hub Resource Get Stats
      description: Get the statistics from an IoT hub.
      operationId: IotHubResource_GetStats
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameiothubstats-get
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
      - Iot Hub Resource Stats
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/skus:
    get:
      summary: Iot Hub Resource Get Valid Skus
      description: Get the list of valid SKUs for an IoT hub.
      operationId: IotHubResource_GetValidSkus
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameskus-get
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
      - Iot Hub Resource Valid Skus
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/eventHubEndpoints/{eventHubEndpointName}/ConsumerGroups
  : get:
      summary: Iot Hub Resource List Event Hub Consumer Groups
      description: Get a list of the consumer groups in the Event Hub-compatible device-to-cloud
        endpoint in an IoT hub.
      operationId: IotHubResource_ListEventHubConsumerGroups
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroups-get
      parameters:
      - in: path
        name: eventHubEndpointName
        description: The name of the Event Hub-compatible endpoint
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
      - Iot Hub Resource Event Hub Consumer Groups
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/eventHubEndpoints/{eventHubEndpointName}/ConsumerGroups/{name}
  : get:
      summary: Iot Hub Resource Get Event Hub Consumer Group
      description: Get a consumer group from the Event Hub-compatible device-to-cloud
        endpoint for an IoT hub.
      operationId: IotHubResource_GetEventHubConsumerGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-get
      parameters:
      - in: path
        name: eventHubEndpointName
        description: The name of the Event Hub-compatible endpoint in the IoT hub
      - in: path
        name: name
        description: The name of the consumer group to retrieve
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
      - Iot Hub Resource Event Hub Consumer Group
    put:
      summary: Iot Hub Resource Create Event Hub Consumer Group
      description: Add a consumer group to an Event Hub-compatible endpoint in an
        IoT hub.
      operationId: IotHubResource_CreateEventHubConsumerGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-put
      parameters:
      - in: path
        name: eventHubEndpointName
        description: The name of the Event Hub-compatible endpoint in the IoT hub
      - in: path
        name: name
        description: The name of the consumer group to add
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
      - Iot Hub Resource Event Hub Consumer Group
    delete:
      summary: Iot Hub Resource Delete Event Hub Consumer Group
      description: Delete a consumer group from an Event Hub-compatible endpoint in
        an IoT hub.
      operationId: IotHubResource_DeleteEventHubConsumerGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-delete
      parameters:
      - in: path
        name: eventHubEndpointName
        description: The name of the Event Hub-compatible endpoint in the IoT hub
      - in: path
        name: name
        description: The name of the consumer group to delete
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
      - Iot Hub Resource Event Hub Consumer Group
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/jobs:
    get:
      summary: Iot Hub Resource List Jobs
      description: 'Get a list of all the jobs in an IoT hub. For more information,
        see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.'
      operationId: IotHubResource_ListJobs
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamejobs-get
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
      - Iot Hub Resource Jobs
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/jobs/{jobId}
  : get:
      summary: Iot Hub Resource Get Job
      description: 'Get the details of a job from an IoT hub. For more information,
        see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.'
      operationId: IotHubResource_GetJob
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamejobsjobid-get
      parameters:
      - in: path
        name: jobId
        description: The job identifier
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
      - Iot Hub Resource Job
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/quotaMetrics
  : get:
      summary: Iot Hub Resource Get Quota Metrics
      description: Get the quota metrics for an IoT hub.
      operationId: IotHubResource_GetQuotaMetrics
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamequotametrics-get
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
      - Iot Hub Resource Quota Metrics
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