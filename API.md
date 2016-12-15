# APIs
* [Put Subscription](#put-subscription )
* [ScaleUp InfraRole](#scaleup-infrarole )
* [Get InfraRole](#get-infrarole )
* [Delete InfraRole](#delete-infrarole )
* [Get InfraRoles](#get-infraroles )
* [Get OperationResult](#get-operationresult )
* [PowerOff InfraRoleInstance](#poweroff-infraroleinstance )
* [PowerOn InfraRoleInstance](#poweron-infraroleinstance )
* [Shutdown InfraRoleInstance](#shutdown-infraroleinstance )
* [Reboot InfraRoleInstance](#reboot-infraroleinstance )
* [Get InfraRoleInstance](#get-infraroleinstance )
* [Delete InfraRoleInstance](#delete-infraroleinstance )
* [Get InfraRoleInstances](#get-infraroleinstances )
* [Get FabricLocation](#get-fabriclocation )
* [Delete FabricLocation](#delete-fabriclocation )
* [Put FabricLocation](#put-fabriclocation )
* [Get FabricLocations](#get-fabriclocations )
* [PowerOff ScaleUnitNode](#poweroff-scaleunitnode )
* [PowerOn ScaleUnitNode](#poweron-scaleunitnode )
* [Get ScaleUnitNode](#get-scaleunitnode )
* [Delete ScaleUnitNode](#delete-scaleunitnode )
* [Get ScaleUnitNodes](#get-scaleunitnodes )
* [ScaleOut ScaleUnit](#scaleout-scaleunit )
* [ScaleIn ScaleUnit](#scalein-scaleunit )
* [Get ScaleUnit](#get-scaleunit )
* [Delete ScaleUnit](#delete-scaleunit )
* [Get ScaleUnits](#get-scaleunits )
* [Get EdgeGatewayPool](#get-edgegatewaypool )
* [Delete EdgeGatewayPool](#delete-edgegatewaypool )
* [Get EdgeGatewayPools](#get-edgegatewaypools )
* [Get MacAddressPool](#get-macaddresspool )
* [Delete MacAddressPool](#delete-macaddresspool )
* [Get MacAddressPools](#get-macaddresspools )
* [Get IpPool](#get-ippool )
* [Delete IpPool](#delete-ippool )
* [Get IpPools](#get-ippools )
* [Get LogicalNetwork](#get-logicalnetwork )
* [Delete LogicalNetwork](#delete-logicalnetwork )
* [Get LogicalNetworks](#get-logicalnetworks )
* [Get LogicalSubnet](#get-logicalsubnet )
* [Delete LogicalSubnet](#delete-logicalsubnet )
* [Get LogicalSubnets](#get-logicalsubnets )
* [Get FileShare](#get-fileshare )
* [Delete FileShare](#delete-fileshare )
* [Get FileShares](#get-fileshares )
* [Get Volume](#get-volume )
* [Delete Volume](#delete-volume )
* [Get Volumes](#get-volumes )
* [Get StoragePool](#get-storagepool )
* [Delete StoragePool](#delete-storagepool )
* [Get StoragePools](#get-storagepools )
* [Get StorageSubSystem](#get-storagesubsystem )
* [Delete StorageSubSystem](#delete-storagesubsystem )
* [Get StorageSubSystems](#get-storagesubsystems )

[](#put-subscription )
## Put Subscription
### Endpoint
`PUT:/subscriptions/{subscription}`
### Description
No description provided.
### Parameters
|      Name     |  Type |  Description |  Schema |  Required |  Default |
|:-------------:|:-----:|:------------:|:-------:|:---------:|:--------:|
|  subscription |  Path |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#scaleup-infrarole )
## ScaleUp InfraRole
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoles/{infraRole}/ScaleUp`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|    infraRole    |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-infrarole )
## Get InfraRole
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoles/{infraRole}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|    infraRole    |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                        Schema                       |
|:------------:|:------------:|:---------------------------------------------------:|
|      200     |      OK      |  [ArmResource[InfraRole]](#armresource[infrarole] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-infrarole )
## Delete InfraRole
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoles/{infraRole}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|    infraRole    |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                        Schema                       |
|:------------:|:------------:|:---------------------------------------------------:|
|      200     |      OK      |  [ArmResource[InfraRole]](#armresource[infrarole] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-infraroles )
## Get InfraRoles
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoles`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                           Schema                          |
|:------------:|:------------:|:---------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[InfraRole]](#armresource[infrarole] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-operationresult )
## Get OperationResult
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/{provider}/fabricLocations/{fabricLocation}/operationResults/{operationResult}`
### Description
No description provided.
### Parameters
|       Name       |  Type  |  Description |  Schema |  Required |  Default |
|:----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription   |  Path  |              |   True  |   False   |          |
|  operationResult |  Path  |              |   True  |   False   |          |
|   resourceGroup  |  Path  |              |   True  |   False   |          |
|     provider     |  Path  |              |   True  |   False   |          |
|  fabricLocation  |  Path  |              |   True  |   False   |          |
|    api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#poweroff-infraroleinstance )
## PowerOff InfraRoleInstance
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoleInstances/{infraRoleInstance}/PowerOff`
### Description
No description provided.
### Parameters
|        Name        |  Type  |  Description |  Schema |  Required |  Default |
|:------------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription    |  Path  |              |   True  |   False   |          |
|    resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation   |  Path  |              |   True  |   False   |          |
|  infraRoleInstance |  Path  |              |   True  |   False   |          |
|     api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#poweron-infraroleinstance )
## PowerOn InfraRoleInstance
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoleInstances/{infraRoleInstance}/PowerOn`
### Description
No description provided.
### Parameters
|        Name        |  Type  |  Description |  Schema |  Required |  Default |
|:------------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription    |  Path  |              |   True  |   False   |          |
|    resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation   |  Path  |              |   True  |   False   |          |
|  infraRoleInstance |  Path  |              |   True  |   False   |          |
|     api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#shutdown-infraroleinstance )
## Shutdown InfraRoleInstance
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoleInstances/{infraRoleInstance}/Shutdown`
### Description
No description provided.
### Parameters
|        Name        |  Type  |  Description |  Schema |  Required |  Default |
|:------------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription    |  Path  |              |   True  |   False   |          |
|    resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation   |  Path  |              |   True  |   False   |          |
|  infraRoleInstance |  Path  |              |   True  |   False   |          |
|     api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#reboot-infraroleinstance )
## Reboot InfraRoleInstance
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoleInstances/{infraRoleInstance}/Reboot`
### Description
No description provided.
### Parameters
|        Name        |  Type  |  Description |  Schema |  Required |  Default |
|:------------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription    |  Path  |              |   True  |   False   |          |
|    resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation   |  Path  |              |   True  |   False   |          |
|  infraRoleInstance |  Path  |              |   True  |   False   |          |
|     api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-infraroleinstance )
## Get InfraRoleInstance
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoleInstances/{infraRoleInstance}`
### Description
No description provided.
### Parameters
|        Name        |  Type  |  Description |  Schema |  Required |  Default |
|:------------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription    |  Path  |              |   True  |   False   |          |
|    resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation   |  Path  |              |   True  |   False   |          |
|  infraRoleInstance |  Path  |              |   True  |   False   |          |
|     api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                                Schema                               |
|:------------:|:------------:|:-------------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[InfraRoleInstance]](#armresource[infraroleinstance] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-infraroleinstance )
## Delete InfraRoleInstance
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoleInstances/{infraRoleInstance}`
### Description
No description provided.
### Parameters
|        Name        |  Type  |  Description |  Schema |  Required |  Default |
|:------------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription    |  Path  |              |   True  |   False   |          |
|    resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation   |  Path  |              |   True  |   False   |          |
|  infraRoleInstance |  Path  |              |   True  |   False   |          |
|     api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                                Schema                               |
|:------------:|:------------:|:-------------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[InfraRoleInstance]](#armresource[infraroleinstance] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-infraroleinstances )
## Get InfraRoleInstances
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/infraRoleInstances`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                                   Schema                                  |
|:------------:|:------------:|:-------------------------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[InfraRoleInstance]](#armresource[infraroleinstance] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-fabriclocation )
## Get FabricLocation
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                             Schema                            |
|:------------:|:------------:|:-------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[FabricLocation]](#armresource[fabriclocation] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-fabriclocation )
## Delete FabricLocation
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                             Schema                            |
|:------------:|:------------:|:-------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[FabricLocation]](#armresource[fabriclocation] ) |

### Produces
* application/json
* text/json
* text/html


[](#put-fabriclocation )
## Put FabricLocation
### Endpoint
`PUT:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |             Schema            |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |              True             |   False   |          |
|  resourceGroup  |  Path  |              |              True             |   False   |          |
|  fabricLocation |  Path  |              |              True             |   False   |          |
|   api-version   |  Query |              |              True             |   False   |          |
|     resource    |  Body  |              |  [ArmResource](#armresource ) |    True   |   False  |

### Responses
|  Status Code |  Description |                             Schema                            |
|:------------:|:------------:|:-------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[FabricLocation]](#armresource[fabriclocation] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-fabriclocations )
## Get FabricLocations
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations`
### Description
No description provided.
### Parameters
|      Name      |  Type  |  Description |  Schema |  Required |  Default |
|:--------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|  subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup |  Path  |              |   True  |   False   |          |
|   api-version  |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                                Schema                               |
|:------------:|:------------:|:-------------------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[FabricLocation]](#armresource[fabriclocation] )] |

### Produces
* application/json
* text/json
* text/html


[](#poweroff-scaleunitnode )
## PowerOff ScaleUnitNode
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/scaleUnitNodes/{scaleUnitNode}/PowerOff`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |                Schema               |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |                 True                |   False   |          |
|  resourceGroup  |  Path  |              |                 True                |   False   |          |
|  fabricLocation |  Path  |              |                 True                |   False   |          |
|  scaleUnitNode  |  Path  |              |                 True                |   False   |          |
|   api-version   |  Query |              |                 True                |   False   |          |
|  asyncOperation |  Body  |              |  [AsyncOperation](#asyncoperation ) |    True   |   False  |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#poweron-scaleunitnode )
## PowerOn ScaleUnitNode
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/scaleUnitNodes/{scaleUnitNode}/PowerOn`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |                Schema               |  Required |  Default |
|:---------------:|:------:|:------------:|:-----------------------------------:|:---------:|:--------:|
|   subscription  |  Path  |              |                 True                |   False   |          |
|  resourceGroup  |  Path  |              |                 True                |   False   |          |
|  fabricLocation |  Path  |              |                 True                |   False   |          |
|  scaleUnitNode  |  Path  |              |                 True                |   False   |          |
|   api-version   |  Query |              |                 True                |   False   |          |
|  asyncOperation |  Body  |              |  [AsyncOperation](#asyncoperation ) |    True   |   False  |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-scaleunitnode )
## Get ScaleUnitNode
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/scaleUnitNodes/{scaleUnitNode}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|  scaleUnitNode  |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                            Schema                           |
|:------------:|:------------:|:-----------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[ScaleUnitNode]](#armresource[scaleunitnode] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-scaleunitnode )
## Delete ScaleUnitNode
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/scaleUnitNodes/{scaleUnitNode}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|  scaleUnitNode  |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                            Schema                           |
|:------------:|:------------:|:-----------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[ScaleUnitNode]](#armresource[scaleunitnode] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-scaleunitnodes )
## Get ScaleUnitNodes
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/scaleUnitNodes`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                               Schema                              |
|:------------:|:------------:|:-----------------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[ScaleUnitNode]](#armresource[scaleunitnode] )] |

### Produces
* application/json
* text/json
* text/html


[](#scaleout-scaleunit )
## ScaleOut ScaleUnit
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/scaleUnits/{scaleUnit}/ScaleOut`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |                          Schema                         |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------------------------------------------------------:|:---------:|:--------:|
|    subscription   |  Path  |              |                           True                          |   False   |          |
|   resourceGroup   |  Path  |              |                           True                          |   False   |          |
|   fabricLocation  |  Path  |              |                           True                          |   False   |          |
|     scaleUnit     |  Path  |              |                           True                          |   False   |          |
|    api-version    |  Query |              |                           True                          |   False   |          |
|  serversToBeAdded |  Body  |              |  [BareMetalNodeDescription](#baremetalnodedescription ) |    True   |   False  |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#scalein-scaleunit )
## ScaleIn ScaleUnit
### Endpoint
`POST:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/scaleUnits/{scaleUnit}/ScaleIn`
### Description
No description provided.
### Parameters
|         Name        |  Type  |  Description |                          Schema                         |  Required |  Default |
|:-------------------:|:------:|:------------:|:-------------------------------------------------------:|:---------:|:--------:|
|     subscription    |  Path  |              |                           True                          |   False   |          |
|    resourceGroup    |  Path  |              |                           True                          |   False   |          |
|    fabricLocation   |  Path  |              |                           True                          |   False   |          |
|      scaleUnit      |  Path  |              |                           True                          |   False   |          |
|     api-version     |  Query |              |                           True                          |   False   |          |
|  serversToBeRemoved |  Body  |              |  [BareMetalNodeDescription](#baremetalnodedescription ) |    True   |   False  |

### Responses
|  Status Code |  Description |  Schema |
|:------------:|:------------:|:-------:|
|      200     |      OK      |  Object |

### Produces
* application/json
* text/json
* text/html


[](#get-scaleunit )
## Get ScaleUnit
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/scaleUnits/{scaleUnit}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|    scaleUnit    |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                        Schema                       |
|:------------:|:------------:|:---------------------------------------------------:|
|      200     |      OK      |  [ArmResource[ScaleUnit]](#armresource[scaleunit] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-scaleunit )
## Delete ScaleUnit
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/scaleUnits/{scaleUnit}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|    scaleUnit    |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                        Schema                       |
|:------------:|:------------:|:---------------------------------------------------:|
|      200     |      OK      |  [ArmResource[ScaleUnit]](#armresource[scaleunit] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-scaleunits )
## Get ScaleUnits
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/scaleUnits`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                           Schema                          |
|:------------:|:------------:|:---------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[ScaleUnit]](#armresource[scaleunit] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-edgegatewaypool )
## Get EdgeGatewayPool
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/edgeGatewayPools/{edgeGatewayPool}`
### Description
No description provided.
### Parameters
|       Name       |  Type  |  Description |  Schema |  Required |  Default |
|:----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription   |  Path  |              |   True  |   False   |          |
|   resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation  |  Path  |              |   True  |   False   |          |
|  edgeGatewayPool |  Path  |              |   True  |   False   |          |
|    api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                              Schema                             |
|:------------:|:------------:|:---------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[EdgeGatewayPool]](#armresource[edgegatewaypool] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-edgegatewaypool )
## Delete EdgeGatewayPool
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/edgeGatewayPools/{edgeGatewayPool}`
### Description
No description provided.
### Parameters
|       Name       |  Type  |  Description |  Schema |  Required |  Default |
|:----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription   |  Path  |              |   True  |   False   |          |
|   resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation  |  Path  |              |   True  |   False   |          |
|  edgeGatewayPool |  Path  |              |   True  |   False   |          |
|    api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                              Schema                             |
|:------------:|:------------:|:---------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[EdgeGatewayPool]](#armresource[edgegatewaypool] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-edgegatewaypools )
## Get EdgeGatewayPools
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/edgeGatewayPools`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                                 Schema                                |
|:------------:|:------------:|:---------------------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[EdgeGatewayPool]](#armresource[edgegatewaypool] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-macaddresspool )
## Get MacAddressPool
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/macAddressPools/{macAddressPool}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|  macAddressPool |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                             Schema                            |
|:------------:|:------------:|:-------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[MacAddressPool]](#armresource[macaddresspool] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-macaddresspool )
## Delete MacAddressPool
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/macAddressPools/{macAddressPool}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|  macAddressPool |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                             Schema                            |
|:------------:|:------------:|:-------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[MacAddressPool]](#armresource[macaddresspool] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-macaddresspools )
## Get MacAddressPools
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/macAddressPools`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                                Schema                               |
|:------------:|:------------:|:-------------------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[MacAddressPool]](#armresource[macaddresspool] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-ippool )
## Get IpPool
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/ipPools/{ipPool}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|      ipPool     |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                     Schema                    |
|:------------:|:------------:|:---------------------------------------------:|
|      200     |      OK      |  [ArmResource[IpPool]](#armresource[ippool] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-ippool )
## Delete IpPool
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/ipPools/{ipPool}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|      ipPool     |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                     Schema                    |
|:------------:|:------------:|:---------------------------------------------:|
|      200     |      OK      |  [ArmResource[IpPool]](#armresource[ippool] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-ippools )
## Get IpPools
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/ipPools`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                        Schema                       |
|:------------:|:------------:|:---------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[IpPool]](#armresource[ippool] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-logicalnetwork )
## Get LogicalNetwork
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|  logicalNetwork |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                             Schema                            |
|:------------:|:------------:|:-------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[LogicalNetwork]](#armresource[logicalnetwork] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-logicalnetwork )
## Delete LogicalNetwork
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|  logicalNetwork |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                             Schema                            |
|:------------:|:------------:|:-------------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[LogicalNetwork]](#armresource[logicalnetwork] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-logicalnetworks )
## Get LogicalNetworks
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                                Schema                               |
|:------------:|:------------:|:-------------------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[LogicalNetwork]](#armresource[logicalnetwork] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-logicalsubnet )
## Get LogicalSubnet
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets/{logicalSubnet}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|  logicalNetwork |  Path  |              |   True  |   False   |          |
|  logicalSubnet  |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                            Schema                           |
|:------------:|:------------:|:-----------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[LogicalSubnet]](#armresource[logicalsubnet] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-logicalsubnet )
## Delete LogicalSubnet
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets/{logicalSubnet}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|  logicalNetwork |  Path  |              |   True  |   False   |          |
|  logicalSubnet  |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                            Schema                           |
|:------------:|:------------:|:-----------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[LogicalSubnet]](#armresource[logicalsubnet] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-logicalsubnets )
## Get LogicalSubnets
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/logicalNetworks/{logicalNetwork}/logicalSubnets`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|  logicalNetwork |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                               Schema                              |
|:------------:|:------------:|:-----------------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[LogicalSubnet]](#armresource[logicalsubnet] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-fileshare )
## Get FileShare
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/fileShares/{fileShare}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|    fileShare    |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                        Schema                       |
|:------------:|:------------:|:---------------------------------------------------:|
|      200     |      OK      |  [ArmResource[FileShare]](#armresource[fileshare] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-fileshare )
## Delete FileShare
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/fileShares/{fileShare}`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|    fileShare    |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                        Schema                       |
|:------------:|:------------:|:---------------------------------------------------:|
|      200     |      OK      |  [ArmResource[FileShare]](#armresource[fileshare] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-fileshares )
## Get FileShares
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/fileShares`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                           Schema                          |
|:------------:|:------------:|:---------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[FileShare]](#armresource[fileshare] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-volume )
## Get Volume
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/storagePools/{storagePool}/volumes/{volume}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |   True  |   False   |          |
|   resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation  |  Path  |              |   True  |   False   |          |
|  storageSubSystem |  Path  |              |   True  |   False   |          |
|    storagePool    |  Path  |              |   True  |   False   |          |
|       volume      |  Path  |              |   True  |   False   |          |
|    api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                     Schema                    |
|:------------:|:------------:|:---------------------------------------------:|
|      200     |      OK      |  [ArmResource[Volume]](#armresource[volume] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-volume )
## Delete Volume
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/storagePools/{storagePool}/volumes/{volume}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |   True  |   False   |          |
|   resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation  |  Path  |              |   True  |   False   |          |
|  storageSubSystem |  Path  |              |   True  |   False   |          |
|    storagePool    |  Path  |              |   True  |   False   |          |
|       volume      |  Path  |              |   True  |   False   |          |
|    api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                     Schema                    |
|:------------:|:------------:|:---------------------------------------------:|
|      200     |      OK      |  [ArmResource[Volume]](#armresource[volume] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-volumes )
## Get Volumes
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/storagePools/{storagePool}/volumes`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |   True  |   False   |          |
|   resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation  |  Path  |              |   True  |   False   |          |
|  storageSubSystem |  Path  |              |   True  |   False   |          |
|    storagePool    |  Path  |              |   True  |   False   |          |
|    api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                        Schema                       |
|:------------:|:------------:|:---------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[Volume]](#armresource[volume] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-storagepool )
## Get StoragePool
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/storagePools/{storagePool}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |   True  |   False   |          |
|   resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation  |  Path  |              |   True  |   False   |          |
|  storageSubSystem |  Path  |              |   True  |   False   |          |
|    storagePool    |  Path  |              |   True  |   False   |          |
|    api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                          Schema                         |
|:------------:|:------------:|:-------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[StoragePool]](#armresource[storagepool] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-storagepool )
## Delete StoragePool
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/storagePools/{storagePool}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |   True  |   False   |          |
|   resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation  |  Path  |              |   True  |   False   |          |
|  storageSubSystem |  Path  |              |   True  |   False   |          |
|    storagePool    |  Path  |              |   True  |   False   |          |
|    api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                          Schema                         |
|:------------:|:------------:|:-------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[StoragePool]](#armresource[storagepool] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-storagepools )
## Get StoragePools
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}/storagePools`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |   True  |   False   |          |
|   resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation  |  Path  |              |   True  |   False   |          |
|  storageSubSystem |  Path  |              |   True  |   False   |          |
|    api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                             Schema                            |
|:------------:|:------------:|:-------------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[StoragePool]](#armresource[storagepool] )] |

### Produces
* application/json
* text/json
* text/html


[](#get-storagesubsystem )
## Get StorageSubSystem
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |   True  |   False   |          |
|   resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation  |  Path  |              |   True  |   False   |          |
|  storageSubSystem |  Path  |              |   True  |   False   |          |
|    api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                            Schema                           |
|:------------:|:------------:|:-----------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[StorageSystem]](#armresource[storagesystem] ) |

### Produces
* application/json
* text/json
* text/html


[](#delete-storagesubsystem )
## Delete StorageSubSystem
### Endpoint
`DELETE:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems/{storageSubSystem}`
### Description
No description provided.
### Parameters
|        Name       |  Type  |  Description |  Schema |  Required |  Default |
|:-----------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|    subscription   |  Path  |              |   True  |   False   |          |
|   resourceGroup   |  Path  |              |   True  |   False   |          |
|   fabricLocation  |  Path  |              |   True  |   False   |          |
|  storageSubSystem |  Path  |              |   True  |   False   |          |
|    api-version    |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                            Schema                           |
|:------------:|:------------:|:-----------------------------------------------------------:|
|      200     |      OK      |  [ArmResource[StorageSystem]](#armresource[storagesystem] ) |

### Produces
* application/json
* text/json
* text/html


[](#get-storagesubsystems )
## Get StorageSubSystems
### Endpoint
`GET:/subscriptions/{subscription}/resourceGroups/{resourceGroup}/providers/Microsoft.Fabric.Admin/fabricLocations/{fabricLocation}/storageSubSystems`
### Description
No description provided.
### Parameters
|       Name      |  Type  |  Description |  Schema |  Required |  Default |
|:---------------:|:------:|:------------:|:-------:|:---------:|:--------:|
|   subscription  |  Path  |              |   True  |   False   |          |
|  resourceGroup  |  Path  |              |   True  |   False   |          |
|  fabricLocation |  Path  |              |   True  |   False   |          |
|   api-version   |  Query |              |   True  |   False   |          |

### Responses
|  Status Code |  Description |                               Schema                              |
|:------------:|:------------:|:-----------------------------------------------------------------:|
|      200     |      OK      |  List[[ArmResource[StorageSystem]](#armresource[storagesystem] )] |

### Produces
* application/json
* text/json
* text/html


# Definitions
[](#ArmResource[InfraRole] )

### ArmResource[InfraRole]
|   Property  |  Description |           Schema          |
|:-----------:|:------------:|:-------------------------:|
|      Id     |              |           String          |
|     Name    |              |           String          |
|     Type    |              |           String          |
|   Location  |              |           String          |
|     Tags    |              |    Map[String, String]    |
|  Properties |              |  [InfraRole](#infrarole ) |

[](#InfraRole )

### InfraRole
|  Property  |  Description |     Schema    |
|:----------:|:------------:|:-------------:|
|  Instances |              |  List[String] |

[](#ArmResource[InfraRoleInstance] )

### ArmResource[InfraRoleInstance]
|   Property  |  Description |                   Schema                  |
|:-----------:|:------------:|:-----------------------------------------:|
|      Id     |              |                   String                  |
|     Name    |              |                   String                  |
|     Type    |              |                   String                  |
|   Location  |              |                   String                  |
|     Tags    |              |            Map[String, String]            |
|  Properties |              |  [InfraRoleInstance](#infraroleinstance ) |

[](#InfraRoleInstance )

### InfraRoleInstance
|  Property  |  Description |                       Schema                      |
|:----------:|:------------:|:-------------------------------------------------:|
|  ScaleUnit |              |                       String                      |
|    Size    |              |  [InfraRoleInstanceSize](#infraroleinstancesize ) |
|    State   |              |                       String                      |

[](#InfraRoleInstanceSize )

### InfraRoleInstanceSize
|  Property |  Description |  Schema  |
|:---------:|:------------:|:--------:|
|  MemoryGb |              |  Number  |
|   Cores   |              |  Integer |

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

[](#ArmResource[FabricLocation] )

### ArmResource[FabricLocation]
|   Property  |  Description |                Schema               |
|:-----------:|:------------:|:-----------------------------------:|
|      Id     |              |                String               |
|     Name    |              |                String               |
|     Type    |              |                String               |
|   Location  |              |                String               |
|     Tags    |              |         Map[String, String]         |
|  Properties |              |  [FabricLocation](#fabriclocation ) |

[](#FabricLocation )

### FabricLocation
|Property|Description|Schema|
|:-:|:-:|:-:|

[](#AsyncOperation )

### AsyncOperation
|   Property   |  Description |  Schema |
|:------------:|:------------:|:-------:|
|  OperationId |              |  String |

[](#ArmResource[ScaleUnitNode] )

### ArmResource[ScaleUnitNode]
|   Property  |  Description |               Schema              |
|:-----------:|:------------:|:---------------------------------:|
|      Id     |              |               String              |
|     Name    |              |               String              |
|     Type    |              |               String              |
|   Location  |              |               String              |
|     Tags    |              |        Map[String, String]        |
|  Properties |              |  [ScaleUnitNode](#scaleunitnode ) |

[](#ScaleUnitNode )

### ScaleUnitNode
|      Property      |  Description |                   Schema                  |
|:------------------:|:------------:|:-----------------------------------------:|
|       Status       |              |                   String                  |
|     PowerState     |              |                   String                  |
|     BmcAddress     |              |                   String                  |
|     ClusterName    |              |                   String                  |
|     ClusterUri     |              |                   String                  |
|  InMaintenanceMode |              |                  Boolean                  |
|       Vendor       |              |                   String                  |
|        Model       |              |                   String                  |
|    SerialNumber    |              |                   String                  |
|     BiosVersion    |              |                   String                  |
|      Capacity      |              |  [ScaleUnitCapacity](#scaleunitcapacity ) |

[](#ScaleUnitCapacity )

### ScaleUnitCapacity
|   Property   |  Description |  Schema  |
|:------------:|:------------:|:--------:|
|  TotalMemory |              |  Integer |
|  TotalCores  |              |  Integer |

[](#BareMetalNodeDescription )

### BareMetalNodeDescription
|    Property   |  Description |  Schema |
|:-------------:|:------------:|:-------:|
|   BmcAddress  |              |  String |
|     Vendor    |              |  String |
|     Model     |              |  String |
|  SerialNumber |              |  String |
|  BiosVersion  |              |  String |
|  ComputerName |              |  String |
|       ID      |              |  String |
|   MacAddress  |              |  String |

[](#ArmResource[ScaleUnit] )

### ArmResource[ScaleUnit]
|   Property  |  Description |           Schema          |
|:-----------:|:------------:|:-------------------------:|
|      Id     |              |           String          |
|     Name    |              |           String          |
|     Type    |              |           String          |
|   Location  |              |           String          |
|     Tags    |              |    Map[String, String]    |
|  Properties |              |  [ScaleUnit](#scaleunit ) |

[](#ScaleUnit )

### ScaleUnit
|       Property      |  Description |                   Schema                  |
|:-------------------:|:------------:|:-----------------------------------------:|
|    ScaleUnitType    |              |                   String                  |
|  LogicalFaultDomain |              |                  Integer                  |
|        Nodes        |              |                List[String]               |
|        State        |              |                   String                  |
|        Model        |              |                   String                  |
|       Capacity      |              |  [ScaleUnitCapacity](#scaleunitcapacity ) |

[](#ArmResource[EdgeGatewayPool] )

### ArmResource[EdgeGatewayPool]
|   Property  |  Description |                 Schema                |
|:-----------:|:------------:|:-------------------------------------:|
|      Id     |              |                 String                |
|     Name    |              |                 String                |
|     Type    |              |                 String                |
|   Location  |              |                 String                |
|     Tags    |              |          Map[String, String]          |
|  Properties |              |  [EdgeGatewayPool](#edgegatewaypool ) |

[](#EdgeGatewayPool )

### EdgeGatewayPool
|              Property             |  Description |     Schema    |
|:---------------------------------:|:------------:|:-------------:|
|            GatewayType            |              |     String    |
|          NumberOfGateways         |              |    Integer    |
|       RedundantGatewayCount       |              |    Integer    |
|  GatewayCapacityKiloBitsPerSecond |              |    Integer    |
|          PublicIpAddress          |              |     String    |
|            GreVipSubnet           |              |     String    |
|            EdgeGateways           |              |  List[String] |

[](#ArmResource[MacAddressPool] )

### ArmResource[MacAddressPool]
|   Property  |  Description |                Schema               |
|:-----------:|:------------:|:-----------------------------------:|
|      Id     |              |                String               |
|     Name    |              |                String               |
|     Type    |              |                String               |
|   Location  |              |                String               |
|     Tags    |              |         Map[String, String]         |
|  Properties |              |  [MacAddressPool](#macaddresspool ) |

[](#MacAddressPool )

### MacAddressPool
|            Property            |  Description |        Schema        |
|:------------------------------:|:------------:|:--------------------:|
|            Metadata            |              |  Map[String, String] |
|         StartMacAddress        |              |        String        |
|          EndMacAddress         |              |        String        |
|  NumberOfAllocatedMacAddresses |              |        Integer       |
|  NumberOfAvailableMacAddresses |              |        Integer       |

[](#ArmResource[IpPool] )

### ArmResource[IpPool]
|   Property  |  Description |        Schema        |
|:-----------:|:------------:|:--------------------:|
|      Id     |              |        String        |
|     Name    |              |        String        |
|     Type    |              |        String        |
|   Location  |              |        String        |
|     Tags    |              |  Map[String, String] |
|  Properties |              |  [IpPool](#ippool )  |

[](#IpPool )

### IpPool
|             Property             |  Description |  Schema  |
|:--------------------------------:|:------------:|:--------:|
|            IpPoolName            |              |  String  |
|          StartIpAddress          |              |  String  |
|           EndIpAddress           |              |  String  |
|        NumberOfIpAddresses       |              |  Integer |
|   NumberOfAllocatedIpAddresses   |              |  Integer |
|  NumberOfIpAddressesInTransition |              |  Integer |

[](#ArmResource[LogicalNetwork] )

### ArmResource[LogicalNetwork]
|   Property  |  Description |                Schema               |
|:-----------:|:------------:|:-----------------------------------:|
|      Id     |              |                String               |
|     Name    |              |                String               |
|     Type    |              |                String               |
|   Location  |              |                String               |
|     Tags    |              |         Map[String, String]         |
|  Properties |              |  [LogicalNetwork](#logicalnetwork ) |

[](#LogicalNetwork )

### LogicalNetwork
|            Property           |  Description |        Schema        |
|:-----------------------------:|:------------:|:--------------------:|
|       LogicalNetworkName      |              |        String        |
|            Metadata           |              |  Map[String, String] |
|  NetworkVirtualizationEnabled |              |        Boolean       |
|            Subnets            |              |     List[String]     |

[](#ArmResource[LogicalSubnet] )

### ArmResource[LogicalSubnet]
|   Property  |  Description |               Schema              |
|:-----------:|:------------:|:---------------------------------:|
|      Id     |              |               String              |
|     Name    |              |               String              |
|     Type    |              |               String              |
|   Location  |              |               String              |
|     Tags    |              |        Map[String, String]        |
|  Properties |              |  [LogicalSubnet](#logicalsubnet ) |

[](#LogicalSubnet )

### LogicalSubnet
|      Property      |  Description |        Schema        |
|:------------------:|:------------:|:--------------------:|
|       IpPools      |              |     List[String]     |
|      IsPublic      |              |        Boolean       |
|  LogicalSubnetName |              |        String        |
|      Metadata      |              |  Map[String, String] |

[](#ArmResource[FileShare] )

### ArmResource[FileShare]
|   Property  |  Description |           Schema          |
|:-----------:|:------------:|:-------------------------:|
|      Id     |              |           String          |
|     Name    |              |           String          |
|     Type    |              |           String          |
|   Location  |              |           String          |
|     Tags    |              |    Map[String, String]    |
|  Properties |              |  [FileShare](#fileshare ) |

[](#FileShare )

### FileShare
|      Property     |  Description |  Schema |
|:-----------------:|:------------:|:-------:|
|  AssociatedVolume |              |  String |
|      UNCPath      |              |  String |

[](#ArmResource[Volume] )

### ArmResource[Volume]
|   Property  |  Description |        Schema        |
|:-----------:|:------------:|:--------------------:|
|      Id     |              |        String        |
|     Name    |              |        String        |
|     Type    |              |        String        |
|   Location  |              |        String        |
|     Tags    |              |  Map[String, String] |
|  Properties |              |  [Volume](#volume )  |

[](#Volume )

### Volume
|     Property     |  Description |  Schema  |
|:----------------:|:------------:|:--------:|
|    FileSystem    |              |  String  |
|  RemainingSizeGB |              |  Integer |
|      SizeGB      |              |  Integer |
|    VolumeLabel   |              |  String  |

[](#ArmResource[StoragePool] )

### ArmResource[StoragePool]
|   Property  |  Description |             Schema            |
|:-----------:|:------------:|:-----------------------------:|
|      Id     |              |             String            |
|     Name    |              |             String            |
|     Type    |              |             String            |
|   Location  |              |             String            |
|     Tags    |              |      Map[String, String]      |
|  Properties |              |  [StoragePool](#storagepool ) |

[](#StoragePool )

### StoragePool
|  Property |  Description |  Schema  |
|:---------:|:------------:|:--------:|
|   SizeGB  |              |  Integer |

[](#ArmResource[StorageSystem] )

### ArmResource[StorageSystem]
|   Property  |  Description |               Schema              |
|:-----------:|:------------:|:---------------------------------:|
|      Id     |              |               String              |
|     Name    |              |               String              |
|     Type    |              |               String              |
|   Location  |              |               String              |
|     Tags    |              |        Map[String, String]        |
|  Properties |              |  [StorageSystem](#storagesystem ) |

[](#StorageSystem )

### StorageSystem
|     Property     |  Description |  Schema  |
|:----------------:|:------------:|:--------:|
|  TotalCapacityGB |              |  Integer |


