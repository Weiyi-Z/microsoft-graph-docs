---
title: "managedTenant resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# managedTenant resource type

Namespace: microsoft.graph.managedTenants

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/managedtenants-entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List managedTenants](../api/managedtenants-managedtenant-list.md)|[microsoft.graph.managedTenants.managedTenant](../resources/managedtenants-managedtenant.md) collection|Get a list of the [managedTenant](../resources/managedtenants-managedtenant.md) objects and their properties.|
|[Create managedTenant](../api/managedtenants-managedtenant-create.md)|[microsoft.graph.managedTenants.managedTenant](../resources/managedtenants-managedtenant.md)|Create a new [managedTenant](../resources/managedtenants-managedtenant.md) object.|
|[Get managedTenant](../api/managedtenants-managedtenant-get.md)|[microsoft.graph.managedTenants.managedTenant](../resources/managedtenants-managedtenant.md)|Read the properties and relationships of a [managedTenant](../resources/managedtenants-managedtenant.md) object.|
|[Update managedTenant](../api/managedtenants-managedtenant-update.md)|[microsoft.graph.managedTenants.managedTenant](../resources/managedtenants-managedtenant.md)|Update the properties of a [managedTenant](../resources/managedtenants-managedtenant.md) object.|
|[Delete managedTenant](../api/managedtenants-managedtenant-delete.md)|None|Deletes a [managedTenant](../resources/managedtenants-managedtenant.md) object.|
|[List tenantTags](../api/managedtenants-managedtenant-list-tenanttags.md)|[microsoft.graph.managedTenants.tenantTag](../resources/managedtenants-tenanttag.md) collection|Get the tenantTag resources from the tenantTags navigation property.|
|[Create tenantTag](../api/managedtenants-managedtenant-post-tenanttags.md)|[microsoft.graph.managedTenants.tenantTag](../resources/managedtenants-tenanttag.md)|Create a new tenantTag object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/managedtenants-entity.md).|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|aggregatedPolicyCompliances|[microsoft.graph.managedTenants.aggregatedPolicyCompliance](../resources/managedtenants-aggregatedpolicycompliance.md) collection|**TODO: Add Description**|
|cloudPcConnections|[microsoft.graph.managedTenants.cloudPcConnection](../resources/managedtenants-cloudpcconnection.md) collection|**TODO: Add Description**|
|cloudPcDevices|[microsoft.graph.managedTenants.cloudPcDevice](../resources/managedtenants-cloudpcdevice.md) collection|**TODO: Add Description**|
|cloudPcsOverview|[microsoft.graph.managedTenants.cloudPcOverview](../resources/managedtenants-cloudpcoverview.md) collection|**TODO: Add Description**|
|conditionalAccessPolicyCoverages|[microsoft.graph.managedTenants.conditionalAccessPolicyCoverage](../resources/managedtenants-conditionalaccesspolicycoverage.md) collection|**TODO: Add Description**|
|credentialUserRegistrationsSummaries|[microsoft.graph.managedTenants.credentialUserRegistrationsSummary](../resources/managedtenants-credentialuserregistrationssummary.md) collection|**TODO: Add Description**|
|deviceCompliancePolicySettingStateSummaries|[microsoft.graph.managedTenants.deviceCompliancePolicySettingStateSummary](../resources/managedtenants-intune-devicecompliancepolicysettingstatesummary.md) collection|**TODO: Add Description**|
|managedDeviceCompliances|[microsoft.graph.managedTenants.managedDeviceCompliance](../resources/managedtenants-manageddevicecompliance.md) collection|**TODO: Add Description**|
|managedDeviceComplianceTrends|[microsoft.graph.managedTenants.managedDeviceComplianceTrend](../resources/managedtenants-manageddevicecompliancetrend.md) collection|**TODO: Add Description**|
|riskyUsers|[microsoft.graph.managedTenants.riskyUser](../resources/managedtenants-riskyuser.md) collection|**TODO: Add Description**|
|tenantTags|[microsoft.graph.managedTenants.tenantTag](../resources/managedtenants-tenanttag.md) collection|**TODO: Add Description**|
|windowsDeviceMalwareStates|[microsoft.graph.managedTenants.windowsDeviceMalwareState](../resources/managedtenants-intune-windowsdevicemalwarestate.md) collection|**TODO: Add Description**|
|windowsProtectionStates|[microsoft.graph.managedTenants.windowsProtectionState](../resources/managedtenants-intune-windowsprotectionstate.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.managedTenants.managedTenant",
  "baseType": "microsoft.graph.entity",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.managedTenants.managedTenant",
  "id": "String (identifier)"
}
```

