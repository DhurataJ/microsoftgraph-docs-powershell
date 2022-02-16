---
external help file: Microsoft.Graph.Identity.Governance-help.xml
Module Name: Microsoft.Graph.Identity.Governance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/set-mgentitlementmanagementaccesspackageassignmentrequestaccesspackagebyref
schema: 2.0.0
---

# Set-MgEntitlementManagementAccessPackageAssignmentRequestAccessPackageByRef

## SYNOPSIS
The access package associated with the accessPackageAssignmentRequest.
An access package defines the collections of resource roles and the policies for how one or more users can get access to those resources.
Read-only.
Nullable.
Supports $expand.

## SYNTAX

### SetExpanded (Default)
```
Set-MgEntitlementManagementAccessPackageAssignmentRequestAccessPackageByRef
 -AccessPackageAssignmentRequestId <String> [-AdditionalProperties <Hashtable>] [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### Set
```
Set-MgEntitlementManagementAccessPackageAssignmentRequestAccessPackageByRef
 -AccessPackageAssignmentRequestId <String> -BodyParameter <Hashtable> [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### SetViaIdentityExpanded
```
Set-MgEntitlementManagementAccessPackageAssignmentRequestAccessPackageByRef
 -InputObject <IIdentityGovernanceIdentity> [-AdditionalProperties <Hashtable>] [-PassThru] [-WhatIf]
 [-Confirm] [<CommonParameters>]
```

### SetViaIdentity
```
Set-MgEntitlementManagementAccessPackageAssignmentRequestAccessPackageByRef
 -InputObject <IIdentityGovernanceIdentity> -BodyParameter <Hashtable> [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
The access package associated with the accessPackageAssignmentRequest.
An access package defines the collections of resource roles and the policies for how one or more users can get access to those resources.
Read-only.
Nullable.
Supports $expand.

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AccessPackageAssignmentRequestId
key: id of accessPackageAssignmentRequest

```yaml
Type: String
Parameter Sets: SetExpanded, Set
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: SetExpanded, SetViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
.

```yaml
Type: Hashtable
Parameter Sets: Set, SetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IIdentityGovernanceIdentity
Parameter Sets: SetViaIdentityExpanded, SetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PassThru
Returns true when the command succeeds

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IIdentityGovernanceIdentity
### System.Collections.Hashtable
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/set-mgentitlementmanagementaccesspackageassignmentrequestaccesspackagebyref](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/set-mgentitlementmanagementaccesspackageassignmentrequestaccesspackagebyref)
