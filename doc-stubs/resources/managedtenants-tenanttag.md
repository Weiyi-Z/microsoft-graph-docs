---
title: "tenantTag resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# tenantTag resource type

Namespace: microsoft.graph.managedTenants

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/managedtenants-entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List tenantTags](../api/managedtenants-tenanttag-list.md)|[microsoft.graph.managedTenants.tenantTag](../resources/managedtenants-tenanttag.md) collection|Get a list of the [tenantTag](../resources/managedtenants-tenanttag.md) objects and their properties.|
|[Create tenantTag](../api/managedtenants-tenanttag-create.md)|[microsoft.graph.managedTenants.tenantTag](../resources/managedtenants-tenanttag.md)|Create a new [tenantTag](../resources/managedtenants-tenanttag.md) object.|
|[Get tenantTag](../api/managedtenants-tenanttag-get.md)|[microsoft.graph.managedTenants.tenantTag](../resources/managedtenants-tenanttag.md)|Read the properties and relationships of a [tenantTag](../resources/managedtenants-tenanttag.md) object.|
|[Update tenantTag](../api/managedtenants-tenanttag-update.md)|[microsoft.graph.managedTenants.tenantTag](../resources/managedtenants-tenanttag.md)|Update the properties of a [tenantTag](../resources/managedtenants-tenanttag.md) object.|
|[Delete tenantTag](../api/managedtenants-tenanttag-delete.md)|None|Deletes a [tenantTag](../resources/managedtenants-tenanttag.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdByUserId|String|**TODO: Add Description**|
|deletedDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/managedtenants-entity.md).|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|managedTenants|[microsoft.graph.managedTenants.managedTenantInfo](../resources/managedtenants-managedtenantinfo.md) collection|**TODO: Add Description**|
|modifiedByUserId|String|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.managedTenants.tenantTag",
  "baseType": "microsoft.graph.entity",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.managedTenants.tenantTag",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "createdByUserId": "String",
  "modifiedByUserId": "String",
  "managedTenants": [
    {
      "@odata.type": "microsoft.graph.managedTenants.managedTenantInfo"
    }
  ],
  "lastModifiedDateTime": "String (timestamp)",
  "deletedDateTime": "String (timestamp)"
}
```

