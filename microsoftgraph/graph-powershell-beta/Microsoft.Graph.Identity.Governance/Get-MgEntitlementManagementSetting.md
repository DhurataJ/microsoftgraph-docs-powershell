---
external help file: Microsoft.Graph.Identity.Governance-help.xml
Module Name: Microsoft.Graph.Identity.Governance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/get-mgentitlementmanagementsetting
schema: 2.0.0
---

# Get-MgEntitlementManagementSetting

## SYNOPSIS
Get settings from identityGovernance

## SYNTAX

```
Get-MgEntitlementManagementSetting [-ExpandProperty <String[]>] [-Property <String[]>] [<CommonParameters>]
```

## DESCRIPTION
Get settings from identityGovernance

## EXAMPLES

### Example 1: Get the identity governance settings
```powershell
Connect-MgGraph -Scopes 'EntitlementManagement.ReadWrite.All'
Get-MgEntitlementManagementSetting

Id        DaysUntilExternalUserDeletedAfterBlocked ExternalUserLifecycleAction
--        ---------------------------------------- ---------------------------
singleton 30                                       BlockSignInAndDelete
```

This example returns the identity governance settings.

## PARAMETERS

### -ExpandProperty
Expand related entities

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Expand

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Property
Select properties to be returned

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: Select

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphEntitlementManagementSettings
## NOTES

ALIASES

## RELATED LINKS
