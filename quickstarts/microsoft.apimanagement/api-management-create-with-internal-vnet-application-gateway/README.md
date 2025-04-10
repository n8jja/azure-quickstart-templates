---
description: This template demonstrates how to Create a instance of Azure API Management on a private network protected by Azure Application Gateway.
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: api-management-create-with-internal-vnet-application-gateway
languages:
- bicep
- json
---
# Create API Management in Internal VNet with App Gateway

![Azure Public Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.apimanagement/api-management-create-with-internal-vnet-application-gateway/PublicLastTestDate.svg)
![Azure Public Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.apimanagement/api-management-create-with-internal-vnet-application-gateway/PublicDeployment.svg)

![Azure US Gov Last Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.apimanagement/api-management-create-with-internal-vnet-application-gateway/FairfaxLastTestDate.svg)
![Azure US Gov Last Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.apimanagement/api-management-create-with-internal-vnet-application-gateway/FairfaxDeployment.svg)

![Best Practice Check](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.apimanagement/api-management-create-with-internal-vnet-application-gateway/BestPracticeResult.svg)
![Cred Scan Check](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.apimanagement/api-management-create-with-internal-vnet-application-gateway/CredScanResult.svg)

![Bicep Version](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.apimanagement/api-management-create-with-internal-vnet-application-gateway/BicepVersion.svg)

[![Deploy To Azure](https://raw.githubusercontent.com/n8jja/azure-quickstart-templates/refs/heads/master/quickstarts/microsoft.apimanagement/api-management-create-with-internal-vnet-application-gateway/zippysdeploy.json)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fquickstarts%2Fmicrosoft.apimanagement%2Fapi-management-create-with-internal-vnet-application-gateway%2Fazuredeploy.json)
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fquickstarts%2Fmicrosoft.apimanagement%2Fapi-management-create-with-internal-vnet-application-gateway%2Fazuredeploy.json)

This template shows an example of how to deploy an Azure API Management service protect by Azure Application Gateway Web Application Firewall.  This also demonstrates how to configure integration with Application Insights and Azure Monitor Log Analytics.  Because the concept being demonstrated in this template requires VNet integration, only Developer or Premium tier Azure API Management tiers can be selected.
`Tags: Microsoft.ApiManagement/service, SystemAssigned, gateways, loggers, diagnostics, Microsoft.Insights/diagnosticSettings, Microsoft.Network/applicationGateways, Microsoft.Insights/components, Microsoft.Network/publicIPAddresses, Microsoft.Network/virtualNetworks, subnets, Microsoft.Network/privateDnsZones, A, virtualNetworkLinks, Microsoft.OperationalInsights/workspaces`
