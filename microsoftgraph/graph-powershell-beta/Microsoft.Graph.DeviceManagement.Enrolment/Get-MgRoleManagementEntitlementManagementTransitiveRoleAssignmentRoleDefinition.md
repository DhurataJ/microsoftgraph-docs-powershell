---
external help file: Microsoft.Graph.DeviceManagement.Enrolment-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Enrolment
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/get-mgrolemanagemententitlementmanagementtransitiveroleassignmentroledefinition
schema: 2.0.0
---

# Get-MgRoleManagementEntitlementManagementTransitiveRoleAssignmentRoleDefinition

## SYNOPSIS
The roleDefinition the assignment is for.
Supports $expand.
roleDefinition.Id will be auto expanded.

## SYNTAX

### Get (Default)
```
Get-MgRoleManagementEntitlementManagementTransitiveRoleAssignmentRoleDefinition
 -UnifiedRoleAssignmentId <String> [-ExpandProperty <String[]>] [-Property <String[]>] [<CommonParameters>]
```

### GetViaIdentity
```
Get-MgRoleManagementEntitlementManagementTransitiveRoleAssignmentRoleDefinition
 -InputObject <IDeviceManagementEnrolmentIdentity> [-ExpandProperty <String[]>] [-Property <String[]>]
 [<CommonParameters>]
```

## DESCRIPTION
The roleDefinition the assignment is for.
Supports $expand.
roleDefinition.Id will be auto expanded.

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

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

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IDeviceManagementEnrolmentIdentity
Parameter Sets: GetViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
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

### -UnifiedRoleAssignmentId
key: id of unifiedRoleAssignment

```yaml
Type: String
Parameter Sets: Get
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IDeviceManagementEnrolmentIdentity
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphUnifiedRoleDefinition
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/get-mgrolemanagemententitlementmanagementtransitiveroleassignmentroledefinition](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.enrolment/get-mgrolemanagemententitlementmanagementtransitiveroleassignmentroledefinition)
