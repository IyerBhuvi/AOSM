---
description: This template leverages the Import ACR module from the bicep registry to import public container images into an Azure Container Registry.
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: deployment-script-azcli-acr-import
languages:
- json
- bicep
---
# Import Container Images into ACR

![Bicep Version](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.resources/deployment-script-azcli-acr-import/BicepVersion.svg)

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2IyerBhuvi%2AOSM%2main%2azuredeploy.json)

## Sample overview

This template leverages the Import ACR module from the bicep registry to import public container images into an Azure Container Registry. A new Azure Container Registry is created.

See the [Import-ACR](https://github.com/Azure/bicep-registry-modules/blob/main/modules/deployment-scripts/import-acr/README.md) module in the Bicep Registry for more information.
See the [docs](https://docs.microsoft.com/azure/azure-resource-manager/templates/deployment-script-template?tabs=CLI) for more information on the deployment script resource.

## Deployment steps

You can click the "deploy to Azure" button at the beginning of this document or follow the instructions for command line deployment using the scripts in the root of this repo.

`Tags: Acr, Import, AzureCli, Microsoft.ContainerRegistry/registries, Microsoft.Resources/deployments, Microsoft.ManagedIdentity/userAssignedIdentities, Microsoft.Authorization/roleAssignments, Microsoft.Resources/deploymentScripts, UserAssigned`
