---
name: Azure IoT Hub
x-slug: azure-iot-hub
description: Jumpstart your Internet of Things project with Microsoft IoT Hub. Connect,
  monitor, and control billions of IoT assets running on a broad set of operating
  systems and protocols. Establish reliable, bi-directional communication with these
  assets, even if they&rsquo;re intermittently connected, and analyze&mdash;and act
  on&mdash;incoming telemetry data. Enhance the security of your IoT solutions by
  using per-device authentication to communicate with devices that have the appropriate
  credentials. Revoke access rights to specific devices to maintain the integrity
  of your system.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure IoT Hub
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/apis.md
specificationVersion: "0.14"
apis:
- name: Azure IoT Hub API Iot Hub Resource Get
  x-api-slug: azure-iot-hub-api
  description: Get the non-security related metadata of an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}
  tags: Iot Hub Resource
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-get-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Create Or Update
  x-api-slug: azure-iot-hub-api
  description: Create or update the metadata of an Iot hub. The usual pattern to modify
    a property is to retrieve the IoT hub metadata and security metadata, and then
    combine them with the modified values in a new body to update the IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}
  tags: Iot Hub Resource
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-put-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Delete
  x-api-slug: azure-iot-hub-api
  description: Delete an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}
  tags: Iot Hub Resource
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-delete-openapi.md
- name: Azure IoT Hub API Iot Hub Resource List By Subscription
  x-api-slug: azure-iot-hub-api
  description: Get all the IoT hubs in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Devices/IotHubs
  tags: Iot Hub Resource Subscription
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidprovidersmicrosoft-devicesiothubs-get-openapi.md
- name: Azure IoT Hub API Iot Hub Resource List By Resource Group
  x-api-slug: azure-iot-hub-api
  description: Get all the IoT hubs in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs
  tags: Iot Hub Resource Resource Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubs-get-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Get Stats
  x-api-slug: azure-iot-hub-api
  description: Get the statistics from an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/IotHubStats
  tags: Iot Hub Resource Stats
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameiothubstats-get-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Get Valid Skus
  x-api-slug: azure-iot-hub-api
  description: Get the list of valid SKUs for an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/skus
  tags: Iot Hub Resource Valid Skus
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameskus-get-openapi.md
- name: Azure IoT Hub API Iot Hub Resource List Event Hub Consumer Groups
  x-api-slug: azure-iot-hub-api
  description: Get a list of the consumer groups in the Event Hub-compatible device-to-cloud
    endpoint in an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/eventHubEndpoints/{eventHubEndpointName}/ConsumerGroups
  tags: Iot Hub Resource Event Hub Consumer Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroups-get-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Get Event Hub Consumer Group
  x-api-slug: azure-iot-hub-api
  description: Get a consumer group from the Event Hub-compatible device-to-cloud
    endpoint for an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/eventHubEndpoints/{eventHubEndpointName}/ConsumerGroups/{name}
  tags: Iot Hub Resource Event Hub Consumer Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-get-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Create Event Hub Consumer Group
  x-api-slug: azure-iot-hub-api
  description: Add a consumer group to an Event Hub-compatible endpoint in an IoT
    hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/eventHubEndpoints/{eventHubEndpointName}/ConsumerGroups/{name}
  tags: Iot Hub Resource Event Hub Consumer Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-put-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Delete Event Hub Consumer Group
  x-api-slug: azure-iot-hub-api
  description: Delete a consumer group from an Event Hub-compatible endpoint in an
    IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/eventHubEndpoints/{eventHubEndpointName}/ConsumerGroups/{name}
  tags: Iot Hub Resource Event Hub Consumer Group
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-delete-openapi.md
- name: Azure IoT Hub API Iot Hub Resource List Jobs
  x-api-slug: azure-iot-hub-api
  description: 'Get a list of all the jobs in an IoT hub. For more information, see:
    https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/jobs
  tags: Iot Hub Resource Jobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamejobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamejobs-get-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Get Job
  x-api-slug: azure-iot-hub-api
  description: 'Get the details of a job from an IoT hub. For more information, see:
    https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/jobs/{jobId}
  tags: Iot Hub Resource Job
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamejobsjobid-get-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Get Quota Metrics
  x-api-slug: azure-iot-hub-api
  description: Get the quota metrics for an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/quotaMetrics
  tags: Iot Hub Resource Quota Metrics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamequotametrics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamequotametrics-get-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Check Name Availability
  x-api-slug: azure-iot-hub-api
  description: Check if an IoT hub name is available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Devices/checkNameAvailability
  tags: Iot Hub Resource Name Availability
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidprovidersmicrosoft-deviceschecknameavailability-post-openapi.md
- name: Azure IoT Hub API Iot Hub Resource List Keys
  x-api-slug: azure-iot-hub-api
  description: 'Get the security metadata for an IoT hub. For more information, see:
    https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/listkeys
  tags: Iot Hub Resource Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamelistkeys-post-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Get Keys For Key Name
  x-api-slug: azure-iot-hub-api
  description: 'Get a shared access policy by name from an IoT hub. For more information,
    see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/IotHubKeys/{keyName}/listkeys
  tags: Iot Hub Resource Keys For Key Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameiothubkeyskeynamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameiothubkeyskeynamelistkeys-post-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Export Devices
  x-api-slug: azure-iot-hub-api
  description: 'Exports all the device identities in the IoT hub identity registry
    to an Azure Storage blob container. For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/exportDevices
  tags: Iot Hub Resource Export Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameexportdevices-post-openapi.md
- name: Azure IoT Hub API Iot Hub Resource Import Devices
  x-api-slug: azure-iot-hub-api
  description: 'Import, update, or delete device identities in the IoT hub identity
    registry from a blob. For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Devices/IotHubs/{resourceName}/importDevices
  tags: Iot Hub Resource Import Devices
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameimportdevices-post-openapi.md
- name: Azure IoT Hub API
  x-api-slug: azure-iot-hub-api
  description: Jumpstart your Internet of Things project with Microsoft IoT Hub. Connect,
    monitor, and control billions of IoT assets running on a broad set of operating
    systems and protocols. Establish reliable, bi-directional communication with these
    assets, even if they&rsquo;re intermittently connected, and analyze&mdash;and
    act on&mdash;incoming telemetry data. Enhance the security of your IoT solutions
    by using per-device authentication to communicate with devices that have the appropriate
    credentials. Revoke access rights to specific devices to maintain the integrity
    of your system.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Azure IoT Hub
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/iot-hub/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/iot-hub/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/iot-hub/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/iot-hub/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---