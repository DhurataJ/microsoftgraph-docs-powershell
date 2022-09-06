---
title: "Migrate from Azure AD PowerShell to the Microsoft Graph PowerShell SDK."
description: "Migrate your applications from Azure AD PowerShell to the Microsoft Graph PowerShell SDK."

ms.topic: conceptual
ms.date: 09/02/2022
author: msewaweru
manager: CelesteDG
ms.author: eunicewaweru
ms.reviewer: maisarissi, ianfarr
---

# Upgrade from Azure AD PowerShell to the Microsoft Graph PowerShell SDK

Azure AD, Azure AD Preview and MSOnline PowerShell modules are headed for deprecation. Microsoft Graph PowerShell is the recommended PowerShell module for interacting with Azure AD and other Microsoft services. Use the information in this article to plan the migration of your applications to Microsoft Graph PowerShell.

## Why upgrade to Microsoft Graph PowerShell?

The following list summarizes the key advantages of using the Microsoft Graph PowerShell SDK:

- **Access to all Microsoft Graph APIs**: Microsoft Graph PowerShell is based on Microsoft Graph API. The Microsoft Graph API includes, in addition to Azure AD, APIs from other Microsoft services like SharePoint, Exchange, and Outlook, all accessed through a single endpoint with a single access token.
- **Supports PowerShell 7**: Microsoft Graph PowerShell module works with PowerShell 7 and later. It's also compatible with Windows PowerShell 5.1.
- **Cross-platform support**: Microsoft Graph PowerShell module works on all platforms including Windows, macOS, and Linux.
- **Supports modern authentication**: Microsoft Graph PowerShell supports the Microsoft Authentication Library (MSAL) which offers more security. For example, you can use Passwordless sign-in experiences.
- **Supports external identities**: Users from other Azure AD tenants can authenticate to services in your tenant with Microsoft Graph PowerShell.
- **Uses least privilege**: Microsoft Graph PowerShell permissions are NOT pre-authorized and users must perform one-time request for app permissions depending on their needs.
- **Advanced queries**: Microsoft Graph PowerShell supports rich, Azure AD queries via eventual consistency.
- **Open source**: Feature teams and the community can create great PowerShell experiences and share them with everyone.
- **Receives regular updates**: Microsoft Graph PowerShell commands are updated regularly to support the latest Graph API updates.

## Upgrading to Microsoft Graph PowerShell

Scripts written in Azure AD PowerShell won't automatically work with Microsoft Graph PowerShell. The new cmdlet names have been designed to be easy to learn. Instead of using `AzureAD` or `AzureADMS` in cmdlet names, use `Mg`. For example, the cmdlet `Get-AzureADUser` is equivalent to `Get-MgUser`. However, migration is more than just becoming familiar with the new cmdlet names. There are renamed modules, parameters, and other important changes.

To find the new cmdlets, see the [Cmdlet map](azuread-msoline-cmdlet-map.md).

We've outlined the following sample process for upgrading your existing scripts. This sample process is broken into two steps: documenting your scripts and actually upgrading your scripts.

### Step 1: Document current scripts

Follow this example criteria to document your current script:

- **Purpose**: What is the main function of the script?
- **Location**: How are you storing and securing the script? Where is it executed from?
- **Frequency of execution**: How frequently is the script run and from what platform?
- **Importance**: What's the business criticality of the script?
- **Length**: How long is the script?
- **Cmdlets used and number of calls**: A list of all cmdlets used and the frequency of your calls to them.
- **Still required**: Can you use existing or new product functionality to do what the script does to achieve the same results?
- **Improvement points**: Can you improve the script? For example, filter to the left of the pipeline, use [modern authentication](/azure/active-directory/authentication/concept-authentication-passwordless), or use the [PSScriptAnalyzer](/powershell/module/psscriptanalyzer/?view=ps-modules) module.

**Overall score**: Optionally, apply a scoring mechanism to each criteria to help you prioritize the upgrade order. This will mean giving each script an overall score based on the sum of each criteria score. For example, **importance** could be categorized as Critical, High, Medium and Low, and the criteria score would be selected from one of the following: Critical - 4, High - 3, Medium - 2, Low -1.

### Step 2: Update current scripts

After documenting your scripts using the example criteria, follow these steps to upgrade your scripts.

- **Start simple / low score** : If you're using a scoring mechanism, test the upgrade with the least complex, less business-critical scripts.
- **Map cmdlets**: Using the [Cmdlet map](azuread-msoline-cmdlet-map.md), get the Microsoft Graph PowerShell equivalents for your cmdlets.
- **Map parameters / switches**: Using the Microsoft Graph PowerShell syntax, map your parameters and switches.
- **Map filters**: Using the Microsoft Graph PowerShell syntax, map your filters.
- **Check cmdlet documentation**: Human updates are frequently occurring to add samples on using the new cmdlets.
- **Use dedicated apps and adhere to least privilege**: Because Microsoft Graph PowerShell permissions are NOT pre-authorized, perform one-time request for permissions depending on your needs.
- **Understand required permissions**: Use [Find-MgGraphCommand](find-mg-graph-command.md) and [Find-MgGraphPermission](find-mg-graph-permission.md) to understand permissions required for the cmdlets.
- **Understand output objects**: Understand the change in output objects in Microsoft Graph PowerShell.
- **Optionally, understand the underlying API**
  - Use `Find-MgGraphCommand` to find the API path the cmdlet calls
  - Use [Graph Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer) to understand the underlying API calls.
  - Reference [API reference content](/graph/api/overview?view=graph-rest-1.0).

#### Example

The equivalent of the `Get-AzureADUser` cmdlet is [Get-MgUser](/powershell/module/microsoft.graph.users/get-mguser?view=graph-powershell-1.0&preserve-view=true). This cmdlet has additional parameters that let you do more with its output. For example, the **-ConsistencyLevel** parameter that allows you to do `Count`, `Filter`, and `Search`.

```powershell
Connect-MgGraph -Scopes 'User.Read.All'
Get-MgUser -ConsistencyLevel eventual -Count userCount -Filter "startsWith(DisplayName, 'a')" -Top 1
```

### Limitations

There are limitations that currently exist in Microsoft Graph PowerShell, either by design or due to some functionality that is yet to be built in.

- There isn't yet an equivalent of **-SearchString** for `Get-AzureADUser` and `Get-AzureADGroup` commands. Use **-Filter** instead. For example, `Get-MgUser -Filter "DisplayName eq 'Lee Gu'"` returns the user whose display name is equal to the specified string.
- Search doesn't yet work for any Azure AD commands.
- You need to use hash tables to pass nested parameters. See a sample of [Nested parameters](https://github.com/microsoftgraph/msgraph-sdk-powershell/blob/dev/samples/9-Applications.ps1#L28-L43).
- **Pro-tip**: Use the Microsoft Graph PowerShell **-ConsistencyLevel** parameter. It lets you do $count! To learn more about the **-ConsistencyLevel** parameter, see [Advanced query parameters](/graph/aad-advanced-queries).

## Next steps

- [Uninstall AzureAD PowerShell](/powershell/azure/active-directory/install-previous-version): Uninstall the old module before installing the new one.
- [Install the Microsoft Graph PowerShell SDK](/graph/powershell/installation): Follow these instructions to install the Microsoft Graph PowerShell SDK.
