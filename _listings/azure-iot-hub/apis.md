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
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/apis.md
specificationVersion: "0.14"
apis:
- name: iotHubClient - Iot Hub Resource Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-get
  description: Get the non-security related metadata of an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-get-openapi.md
- name: iotHubClient - Iot Hub Resource Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-put
  description: Create or update the metadata of an Iot hub. The usual pattern to modify
    a property is to retrieve the IoT hub metadata and security metadata, and then
    combine them with the modified values in a new body to update the IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-put-openapi.md
- name: iotHubClient - Iot Hub Resource Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-delete
  description: Delete an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcename-delete-openapi.md
- name: iotHubClient - Iot Hub Resource List By Subscription
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-devicesiothubs-get
  description: Get all the IoT hubs in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidprovidersmicrosoft-devicesiothubs-get-openapi.md
- name: iotHubClient - Iot Hub Resource List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubs-get
  description: Get all the IoT hubs in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubs-get-openapi.md
- name: iotHubClient - Iot Hub Resource Get Stats
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameiothubstats-get
  description: Get the statistics from an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameiothubstats-get-openapi.md
- name: iotHubClient - Iot Hub Resource Get Valid Skus
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameskus-get
  description: Get the list of valid SKUs for an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameskus-get-openapi.md
- name: iotHubClient - Iot Hub Resource List Event Hub Consumer Groups
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroups-get
  description: Get a list of the consumer groups in the Event Hub-compatible device-to-cloud
    endpoint in an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroups-get-openapi.md
- name: iotHubClient - Iot Hub Resource Get Event Hub Consumer Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-get
  description: Get a consumer group from the Event Hub-compatible device-to-cloud
    endpoint for an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-get-openapi.md
- name: iotHubClient - Iot Hub Resource Create Event Hub Consumer Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-put
  description: Add a consumer group to an Event Hub-compatible endpoint in an IoT
    hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-put-openapi.md
- name: iotHubClient - Iot Hub Resource Delete Event Hub Consumer Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-delete
  description: Delete a consumer group from an Event Hub-compatible endpoint in an
    IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameeventhubendpointseventhubendpointnameconsumergroupsname-delete-openapi.md
- name: iotHubClient - Iot Hub Resource List Jobs
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamejobs-get
  description: 'Get a list of all the jobs in an IoT hub. For more information, see:
    https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamejobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamejobs-get-openapi.md
- name: iotHubClient - Iot Hub Resource Get Job
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamejobsjobid-get
  description: 'Get the details of a job from an IoT hub. For more information, see:
    https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamejobsjobid-get-openapi.md
- name: iotHubClient - Iot Hub Resource Get Quota Metrics
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamequotametrics-get
  description: Get the quota metrics for an IoT hub.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamequotametrics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamequotametrics-get-openapi.md
- name: iotHubClient - Iot Hub Resource Check Name Availability
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-deviceschecknameavailability-post
  description: Check if an IoT hub name is available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidprovidersmicrosoft-deviceschecknameavailability-post-openapi.md
- name: iotHubClient - Iot Hub Resource List Keys
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamelistkeys-post
  description: 'Get the security metadata for an IoT hub. For more information, see:
    https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenamelistkeys-post-openapi.md
- name: iotHubClient - Iot Hub Resource Get Keys For Key Name
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameiothubkeyskeynamelistkeys-post
  description: 'Get a shared access policy by name from an IoT hub. For more information,
    see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-security.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameiothubkeyskeynamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameiothubkeyskeynamelistkeys-post-openapi.md
- name: iotHubClient - Iot Hub Resource Export Devices
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameexportdevices-post
  description: 'Exports all the device identities in the IoT hub identity registry
    to an Azure Storage blob container. For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameexportdevices-post-openapi.md
- name: iotHubClient - Iot Hub Resource Import Devices
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameimportdevices-post
  description: 'Import, update, or delete device identities in the IoT hub identity
    registry from a blob. For more information, see: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-identity-registry#import-and-export-device-identities.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-iot-01-establish.png
  humanURL: https://azure.microsoft.com/en-us/services/iot-hub/
  baseURL: ://management.azure.com//
  tags: Microsoft, Internet of Things, Stack Network, Devices, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-iot-hub/master/_listings/azure-iot-hub/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devicesiothubsresourcenameimportdevices-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.hdinsight.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.iot.hub.stack.network
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