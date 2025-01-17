---
title: PowerShell - Create a custom role in a lab
description: This article provides an Azure PowerShell script that creats a custom role in a lab in Azure DevTest Labs.  
ms.devlang: azurecli
ms.topic: sample
ms.date: 08/11/2020
---

# Use PowerShell to create a custom role in a lab in Azure DevTest Labs

This sample PowerShell script creates a custom role to use in a lab in Azure DevTest Labs. 

[!INCLUDE [updated-for-az](../../../includes/updated-for-az.md)]

[!INCLUDE [sample-powershell-install](../../../includes/sample-powershell-install-no-ssh-az.md)]

## Prerequisites
* **A lab**. The script requires you to have an existing lab. 

## Sample script

[!code-powershell[main](../../../powershell_scripts/devtest-lab/create-custom-role-in-lab/create-custom-role-in-lab.ps1 "Add external user to a lab")]

## Script explanation

This script uses the following commands: 

| Command | Notes |
|---|---|
| [Get-AzProviderOperation](/powershell/module/az.resources/get-azprovideroperation) | Gets the operations for an Azure resource provider that are securable using Azure RBAC. |
| [Get-AzRoleDefinition](/powershell/module/az.resources/get-azroledefinition) | Lists all Azure roles that are available for assignment. |
| [New-AzRoleDefinition](/powershell/module/az.resources/new-azroledefinition) | Creates a custom role. |

## Next steps

For more information on the Azure PowerShell, see [Azure PowerShell documentation](/powershell/).

Additional Azure Lab Services PowerShell script samples can be found in the [Azure Lab Services PowerShell samples](../samples-powershell.md).
