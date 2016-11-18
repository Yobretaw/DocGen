# APIs
* [ScaleUp Application](#scaleup-application )
* [Get Application](#get-application )
* [Delete Application](#delete-application )
* [Put Application](#put-application )
* [Applications ApplicationResources](#applications-applicationresources )
* [Put Subscription](#put-subscription )
* [Get Cluster](#get-cluster )
* [Delete Cluster](#delete-cluster )
* [Put Cluster](#put-cluster )
* [Clusters Clusters](#clusters-clusters )
* [Get FabricLocation](#get-fabriclocation )
* [Delete FabricLocation](#delete-fabriclocation )
* [Put FabricLocation](#put-fabriclocation )
* [FabricLocations FabricLocationResources](#fabriclocations-fabriclocationresources )
* [PowerOff InfraVirtualMachine](#poweroff-infravirtualmachine )
* [PowerOn InfraVirtualMachine](#poweron-infravirtualmachine )
* [Shutdown InfraVirtualMachine](#shutdown-infravirtualmachine )
* [Reboot InfraVirtualMachine](#reboot-infravirtualmachine )
* [Get InfraVirtualMachine](#get-infravirtualmachine )
* [Delete InfraVirtualMachine](#delete-infravirtualmachine )
* [Put InfraVirtualMachine](#put-infravirtualmachine )
* [InfraVirtualMachines InfraVirtualMachines](#infravirtualmachines-infravirtualmachines )
* [Get IpPool](#get-ippool )
* [Delete IpPool](#delete-ippool )
* [Put IpPool](#put-ippool )
* [IpPools IpPoolResources](#ippools-ippoolresources )
* [Get LogicalNetwork](#get-logicalnetwork )
* [Delete LogicalNetwork](#delete-logicalnetwork )
* [Put LogicalNetwork](#put-logicalnetwork )
* [LogicalNetworks LogicalNetworkResources](#logicalnetworks-logicalnetworkresources )
* [Get LogicalSubnet](#get-logicalsubnet )
* [Delete LogicalSubnet](#delete-logicalsubnet )
* [Put LogicalSubnet](#put-logicalsubnet )
* [LogicalSubnets LogicalSubnetResources](#logicalsubnets-logicalsubnetresources )
* [Get MacAddressPool](#get-macaddresspool )
* [Delete MacAddressPool](#delete-macaddresspool )
* [Put MacAddressPool](#put-macaddresspool )
* [MacAddressPools MacAddressPoolResources](#macaddresspools-macaddresspoolresources )
* [Get FileShare](#get-fileshare )
* [Delete FileShare](#delete-fileshare )
* [Put FileShare](#put-fileshare )
* [FileShares FileShareResources](#fileshares-fileshareresources )
* [Get Pool](#get-pool )
* [Delete Pool](#delete-pool )
* [Put Pool](#put-pool )
* [Pools PoolResources](#pools-poolresources )
* [Get StorageSubSystem](#get-storagesubsystem )
* [Delete StorageSubSystem](#delete-storagesubsystem )
* [Put StorageSubSystem](#put-storagesubsystem )
* [StorageSubSystems StorageSystemResources](#storagesubsystems-storagesystemresources )
* [Get Volume](#get-volume )
* [Delete Volume](#delete-volume )
* [Put Volume](#put-volume )
* [Volumes VolumeResources](#volumes-volumeresources )

[](#scaleup-application )
## ScaleUp Application
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/applications/{application}/ScaleUp`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   application   |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#get-application )
## Get Application
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/applications/{application}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   application   |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-application )
## Delete Application
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/applications/{application}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   application   |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-application )
## Put Application
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/applications/{application}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |             Schema            |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |             String            |    True   |          |
|  resourceGroup  |  Path  |              |             String            |    True   |          |
|  fabricLocation |  Path  |              |             String            |    True   |          |
|   application   |  Path  |              |             String            |    True   |          |
|   api-version   |  Query |              |             String            |    True   |          |
|     resource    |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#applications-applicationresources )
## Applications ApplicationResources
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/applications`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#put-subscription )
## Put Subscription
### Endpoint
`PUT:/subscriptions/{subscription}`
### Description
No description provided.
### Parameters
|      Name     |  Type |  Description |  Schema |  Required |  Default |
|:-------------:|:-----:|:------------:|:-------:|:---------:|:--------:|
|  subscription |  Path |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#get-cluster )
## Get Cluster
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/clusters/{cluster}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|     cluster     |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-cluster )
## Delete Cluster
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/clusters/{cluster}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|     cluster     |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-cluster )
## Put Cluster
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/clusters/{cluster}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |             Schema            |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |             String            |    True   |          |
|  resourceGroup  |  Path  |              |             String            |    True   |          |
|  fabricLocation |  Path  |              |             String            |    True   |          |
|     cluster     |  Path  |              |             String            |    True   |          |
|   api-version   |  Query |              |             String            |    True   |          |
|     resource    |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#clusters-clusters )
## Clusters Clusters
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/clusters`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-fabriclocation )
## Get FabricLocation
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-fabriclocation )
## Delete FabricLocation
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-fabriclocation )
## Put FabricLocation
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |             Schema            |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |             String            |    True   |          |
|  resourceGroup  |  Path  |              |             String            |    True   |          |
|  fabricLocation |  Path  |              |             String            |    True   |          |
|   api-version   |  Query |              |             String            |    True   |          |
|     resource    |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#fabriclocations-fabriclocationresources )
## FabricLocations FabricLocationResources
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations`
### Description
No description provided.
### Parameters
|      Name      |  Type  |  Description |  Schema |  Required |  Default |
|:--------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|  subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup |  Path  |              |  String |    True   |          |
|   api-version  |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#poweroff-infravirtualmachine )
## PowerOff InfraVirtualMachine
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraVirtualMachines/{infraVirtualMachine}/PowerOff`
### Description
No description provided.
### Parameters
|         Name         |  Type  |  Description |                Schema               |  Required |  Default |
|:--------------------:|:------:|:------------:|:-----------------------------------:|:---------:|:--------:|
|     subscription     |  Path  |              |                String               |    True   |          |
|     resourceGroup    |  Path  |              |                String               |    True   |          |
|    fabricLocation    |  Path  |              |                String               |    True   |          |
|  infraVirtualMachine |  Path  |              |                String               |    True   |          |
|      api-version     |  Query |              |                String               |    True   |          |
|    asyncOperation    |  Body  |              |  [AsyncOperation](#asyncoperation ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#poweron-infravirtualmachine )
## PowerOn InfraVirtualMachine
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraVirtualMachines/{infraVirtualMachine}/PowerOn`
### Description
No description provided.
### Parameters
|         Name         |  Type  |  Description |                Schema               |  Required |  Default |
|:--------------------:|:------:|:------------:|:-----------------------------------:|:---------:|:--------:|
|     subscription     |  Path  |              |                String               |    True   |          |
|     resourceGroup    |  Path  |              |                String               |    True   |          |
|    fabricLocation    |  Path  |              |                String               |    True   |          |
|  infraVirtualMachine |  Path  |              |                String               |    True   |          |
|      api-version     |  Query |              |                String               |    True   |          |
|    asyncOperation    |  Body  |              |  [AsyncOperation](#asyncoperation ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#shutdown-infravirtualmachine )
## Shutdown InfraVirtualMachine
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraVirtualMachines/{infraVirtualMachine}/Shutdown`
### Description
No description provided.
### Parameters
|         Name         |  Type  |  Description |                Schema               |  Required |  Default |
|:--------------------:|:------:|:------------:|:-----------------------------------:|:---------:|:--------:|
|     subscription     |  Path  |              |                String               |    True   |          |
|     resourceGroup    |  Path  |              |                String               |    True   |          |
|    fabricLocation    |  Path  |              |                String               |    True   |          |
|  infraVirtualMachine |  Path  |              |                String               |    True   |          |
|      api-version     |  Query |              |                String               |    True   |          |
|    asyncOperation    |  Body  |              |  [AsyncOperation](#asyncoperation ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#reboot-infravirtualmachine )
## Reboot InfraVirtualMachine
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraVirtualMachines/{infraVirtualMachine}/Reboot`
### Description
No description provided.
### Parameters
|         Name         |  Type  |  Description |                Schema               |  Required |  Default |
|:--------------------:|:------:|:------------:|:-----------------------------------:|:---------:|:--------:|
|     subscription     |  Path  |              |                String               |    True   |          |
|     resourceGroup    |  Path  |              |                String               |    True   |          |
|    fabricLocation    |  Path  |              |                String               |    True   |          |
|  infraVirtualMachine |  Path  |              |                String               |    True   |          |
|      api-version     |  Query |              |                String               |    True   |          |
|    asyncOperation    |  Body  |              |  [AsyncOperation](#asyncoperation ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#get-infravirtualmachine )
## Get InfraVirtualMachine
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraVirtualMachines/{infraVirtualMachine}`
### Description
No description provided.
### Parameters
|         Name         |  Type  |  Description |  Schema |  Required |  Default |
|:--------------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|     subscription     |  Path  |              |  String |    True   |          |
|     resourceGroup    |  Path  |              |  String |    True   |          |
|    fabricLocation    |  Path  |              |  String |    True   |          |
|  infraVirtualMachine |  Path  |              |  String |    True   |          |
|      api-version     |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-infravirtualmachine )
## Delete InfraVirtualMachine
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraVirtualMachines/{infraVirtualMachine}`
### Description
No description provided.
### Parameters
|         Name         |  Type  |  Description |  Schema |  Required |  Default |
|:--------------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|     subscription     |  Path  |              |  String |    True   |          |
|     resourceGroup    |  Path  |              |  String |    True   |          |
|    fabricLocation    |  Path  |              |  String |    True   |          |
|  infraVirtualMachine |  Path  |              |  String |    True   |          |
|      api-version     |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-infravirtualmachine )
## Put InfraVirtualMachine
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraVirtualMachines/{infraVirtualMachine}`
### Description
No description provided.
### Parameters
|         Name         |  Type  |  Description |             Schema            |  Required |  Default |
|:--------------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|     subscription     |  Path  |              |             String            |    True   |          |
|     resourceGroup    |  Path  |              |             String            |    True   |          |
|    fabricLocation    |  Path  |              |             String            |    True   |          |
|  infraVirtualMachine |  Path  |              |             String            |    True   |          |
|      api-version     |  Query |              |             String            |    True   |          |
|       resource       |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#infravirtualmachines-infravirtualmachines )
## InfraVirtualMachines InfraVirtualMachines
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraVirtualMachines`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-ippool )
## Get IpPool
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets/{logicalSubnet}/ipPools/{ipPool}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|  logicalNetwork |  Path  |              |  String |    True   |          |
|  logicalSubnet  |  Path  |              |  String |    True   |          |
|      ipPool     |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-ippool )
## Delete IpPool
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets/{logicalSubnet}/ipPools/{ipPool}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|  logicalNetwork |  Path  |              |  String |    True   |          |
|  logicalSubnet  |  Path  |              |  String |    True   |          |
|      ipPool     |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-ippool )
## Put IpPool
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets/{logicalSubnet}/ipPools/{ipPool}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |             Schema            |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |             String            |    True   |          |
|  resourceGroup  |  Path  |              |             String            |    True   |          |
|  fabricLocation |  Path  |              |             String            |    True   |          |
|  logicalNetwork |  Path  |              |             String            |    True   |          |
|  logicalSubnet  |  Path  |              |             String            |    True   |          |
|      ipPool     |  Path  |              |             String            |    True   |          |
|   api-version   |  Query |              |             String            |    True   |          |
|     resource    |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#ippools-ippoolresources )
## IpPools IpPoolResources
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets/{logicalSubnet}/ipPools`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|  logicalNetwork |  Path  |              |  String |    True   |          |
|  logicalSubnet  |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-logicalnetwork )
## Get LogicalNetwork
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|  logicalNetwork |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-logicalnetwork )
## Delete LogicalNetwork
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|  logicalNetwork |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-logicalnetwork )
## Put LogicalNetwork
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |             Schema            |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |             String            |    True   |          |
|  resourceGroup  |  Path  |              |             String            |    True   |          |
|  fabricLocation |  Path  |              |             String            |    True   |          |
|  logicalNetwork |  Path  |              |             String            |    True   |          |
|   api-version   |  Query |              |             String            |    True   |          |
|     resource    |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#logicalnetworks-logicalnetworkresources )
## LogicalNetworks LogicalNetworkResources
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-logicalsubnet )
## Get LogicalSubnet
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets/{logicalSubnet}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|  logicalNetwork |  Path  |              |  String |    True   |          |
|  logicalSubnet  |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-logicalsubnet )
## Delete LogicalSubnet
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets/{logicalSubnet}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|  logicalNetwork |  Path  |              |  String |    True   |          |
|  logicalSubnet  |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-logicalsubnet )
## Put LogicalSubnet
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets/{logicalSubnet}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |             Schema            |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |             String            |    True   |          |
|  resourceGroup  |  Path  |              |             String            |    True   |          |
|  fabricLocation |  Path  |              |             String            |    True   |          |
|  logicalNetwork |  Path  |              |             String            |    True   |          |
|  logicalSubnet  |  Path  |              |             String            |    True   |          |
|   api-version   |  Query |              |             String            |    True   |          |
|     resource    |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#logicalsubnets-logicalsubnetresources )
## LogicalSubnets LogicalSubnetResources
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|  logicalNetwork |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-macaddresspool )
## Get MacAddressPool
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/macAddressPools/{macAddressPool}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|  macAddressPool |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-macaddresspool )
## Delete MacAddressPool
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/macAddressPools/{macAddressPool}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|  macAddressPool |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-macaddresspool )
## Put MacAddressPool
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/macAddressPools/{macAddressPool}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |             Schema            |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |             String            |    True   |          |
|  resourceGroup  |  Path  |              |             String            |    True   |          |
|  fabricLocation |  Path  |              |             String            |    True   |          |
|  macAddressPool |  Path  |              |             String            |    True   |          |
|   api-version   |  Query |              |             String            |    True   |          |
|     resource    |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#macaddresspools-macaddresspoolresources )
## MacAddressPools MacAddressPoolResources
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/macAddressPools`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-fileshare )
## Get FileShare
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/fileShares/{fileShare}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|    fileShare    |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-fileshare )
## Delete FileShare
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/fileShares/{fileShare}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|    fileShare    |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-fileshare )
## Put FileShare
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/fileShares/{fileShare}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |             Schema            |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |             String            |    True   |          |
|  resourceGroup  |  Path  |              |             String            |    True   |          |
|  fabricLocation |  Path  |              |             String            |    True   |          |
|    fileShare    |  Path  |              |             String            |    True   |          |
|   api-version   |  Query |              |             String            |    True   |          |
|     resource    |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#fileshares-fileshareresources )
## FileShares FileShareResources
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/fileShares`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-pool )
## Get Pool
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/pools/{pool}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |  String |    True   |          |
|   resourceGroup   |  Path  |              |  String |    True   |          |
|   fabricLocation  |  Path  |              |  String |    True   |          |
|  storageSubSystem |  Path  |              |  String |    True   |          |
|        pool       |  Path  |              |  String |    True   |          |
|    api-version    |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-pool )
## Delete Pool
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/pools/{pool}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |  String |    True   |          |
|   resourceGroup   |  Path  |              |  String |    True   |          |
|   fabricLocation  |  Path  |              |  String |    True   |          |
|  storageSubSystem |  Path  |              |  String |    True   |          |
|        pool       |  Path  |              |  String |    True   |          |
|    api-version    |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-pool )
## Put Pool
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/pools/{pool}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |             Schema            |  Required |  Default |
|:-----------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|    subscription   |  Path  |              |             String            |    True   |          |
|   resourceGroup   |  Path  |              |             String            |    True   |          |
|   fabricLocation  |  Path  |              |             String            |    True   |          |
|  storageSubSystem |  Path  |              |             String            |    True   |          |
|        pool       |  Path  |              |             String            |    True   |          |
|    api-version    |  Query |              |             String            |    True   |          |
|      resource     |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#pools-poolresources )
## Pools PoolResources
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/pools`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |  String |    True   |          |
|   resourceGroup   |  Path  |              |  String |    True   |          |
|   fabricLocation  |  Path  |              |  String |    True   |          |
|  storageSubSystem |  Path  |              |  String |    True   |          |
|    api-version    |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-storagesubsystem )
## Get StorageSubSystem
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |  String |    True   |          |
|   resourceGroup   |  Path  |              |  String |    True   |          |
|   fabricLocation  |  Path  |              |  String |    True   |          |
|  storageSubSystem |  Path  |              |  String |    True   |          |
|    api-version    |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-storagesubsystem )
## Delete StorageSubSystem
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |  String |    True   |          |
|   resourceGroup   |  Path  |              |  String |    True   |          |
|   fabricLocation  |  Path  |              |  String |    True   |          |
|  storageSubSystem |  Path  |              |  String |    True   |          |
|    api-version    |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-storagesubsystem )
## Put StorageSubSystem
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |             Schema            |  Required |  Default |
|:-----------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|    subscription   |  Path  |              |             String            |    True   |          |
|   resourceGroup   |  Path  |              |             String            |    True   |          |
|   fabricLocation  |  Path  |              |             String            |    True   |          |
|  storageSubSystem |  Path  |              |             String            |    True   |          |
|    api-version    |  Query |              |             String            |    True   |          |
|      resource     |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#storagesubsystems-storagesystemresources )
## StorageSubSystems StorageSystemResources
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |  String |    True   |          |
|  resourceGroup  |  Path  |              |  String |    True   |          |
|  fabricLocation |  Path  |              |  String |    True   |          |
|   api-version   |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-volume )
## Get Volume
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/pools/{pool}/volumes/{volume}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |  String |    True   |          |
|   resourceGroup   |  Path  |              |  String |    True   |          |
|   fabricLocation  |  Path  |              |  String |    True   |          |
|  storageSubSystem |  Path  |              |  String |    True   |          |
|        pool       |  Path  |              |  String |    True   |          |
|       volume      |  Path  |              |  String |    True   |          |
|    api-version    |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#delete-volume )
## Delete Volume
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/pools/{pool}/volumes/{volume}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |  String |    True   |          |
|   resourceGroup   |  Path  |              |  String |    True   |          |
|   fabricLocation  |  Path  |              |  String |    True   |          |
|  storageSubSystem |  Path  |              |  String |    True   |          |
|        pool       |  Path  |              |  String |    True   |          |
|       volume      |  Path  |              |  String |    True   |          |
|    api-version    |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#put-volume )
## Put Volume
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/pools/{pool}/volumes/{volume}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |             Schema            |  Required |  Default |
|:-----------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|    subscription   |  Path  |              |             String            |    True   |          |
|   resourceGroup   |  Path  |              |             String            |    True   |          |
|   fabricLocation  |  Path  |              |             String            |    True   |          |
|  storageSubSystem |  Path  |              |             String            |    True   |          |
|        pool       |  Path  |              |             String            |    True   |          |
|       volume      |  Path  |              |             String            |    True   |          |
|    api-version    |  Query |              |             String            |    True   |          |
|      resource     |  Body  |              |  [ArmResource](#armresource ) |    True   |          |

### Responses
|  Status Code |  Description |    Schema   |
|:------------:|:------------:|:-----------:|
|      200     |      OK      |  No Content |

### Produces
* application/json
* text/json
* text/html


[](#volumes-volumeresources )
## Volumes VolumeResources
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/system/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/pools/{pool}/volumes`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |  String |    True   |          |
|   resourceGroup   |  Path  |              |  String |    True   |          |
|   fabricLocation  |  Path  |              |  String |    True   |          |
|  storageSubSystem |  Path  |              |  String |    True   |          |
|        pool       |  Path  |              |  String |    True   |          |
|    api-version    |  Query |              |  String |    True   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


# Definitions
[](#ArmResource )

### ArmResource
|   Property  |  Description |        Schema        |
|:-----------:|:------------:|:--------------------:|
|      Id     |              |        String        |
|     Name    |              |        String        |
|     Type    |              |        String        |
|   Location  |              |        String        |
|     Tags    |              |  Map[String, String] |
|  Properties |              |        Object        |

[](#AsyncOperation )

### AsyncOperation
|   Property   |  Description |  Schema |
|:------------:|:------------:|:-------:|
|  OperationId |              |  String |


