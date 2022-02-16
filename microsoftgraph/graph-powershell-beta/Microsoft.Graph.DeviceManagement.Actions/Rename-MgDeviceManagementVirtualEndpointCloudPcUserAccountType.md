---
external help file: Microsoft.Graph.DeviceManagement.Actions-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Actions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.actions/rename-mgdevicemanagementvirtualendpointcloudpcuseraccounttype
schema: 2.0.0
---

# Rename-MgDeviceManagementVirtualEndpointCloudPcUserAccountType

## SYNOPSIS
Invoke action changeUserAccountType

## SYNTAX

### ChangeExpanded (Default)
```
Rename-MgDeviceManagementVirtualEndpointCloudPcUserAccountType -CloudPcId <String>
 [-AdditionalProperties <Hashtable>] [-UserAccountType <String>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### Change
```
Rename-MgDeviceManagementVirtualEndpointCloudPcUserAccountType -CloudPcId <String>
 -BodyParameter <IPathsFjf5ZaDevicemanagementVirtualendpointCloudpcsCloudpcIdMicrosoftGraphChangeuseraccounttypePostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ChangeViaIdentityExpanded
```
Rename-MgDeviceManagementVirtualEndpointCloudPcUserAccountType -InputObject <IDeviceManagementActionsIdentity>
 [-AdditionalProperties <Hashtable>] [-UserAccountType <String>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### ChangeViaIdentity
```
Rename-MgDeviceManagementVirtualEndpointCloudPcUserAccountType -InputObject <IDeviceManagementActionsIdentity>
 -BodyParameter <IPathsFjf5ZaDevicemanagementVirtualendpointCloudpcsCloudpcIdMicrosoftGraphChangeuseraccounttypePostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action changeUserAccountType

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: ChangeExpanded, ChangeViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
.
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IPathsFjf5ZaDevicemanagementVirtualendpointCloudpcsCloudpcIdMicrosoftGraphChangeuseraccounttypePostRequestbodyContentApplicationJsonSchema
Parameter Sets: Change, ChangeViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CloudPcId
key: id of cloudPC

```yaml
Type: String
Parameter Sets: ChangeExpanded, Change
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IDeviceManagementActionsIdentity
Parameter Sets: ChangeViaIdentityExpanded, ChangeViaIdentity
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

### -UserAccountType
cloudPcUserAccountType

```yaml
Type: String
Parameter Sets: ChangeExpanded, ChangeViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
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

### Microsoft.Graph.PowerShell.Models.IDeviceManagementActionsIdentity
### Microsoft.Graph.PowerShell.Models.IPathsFjf5ZaDevicemanagementVirtualendpointCloudpcsCloudpcIdMicrosoftGraphChangeuseraccounttypePostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.actions/rename-mgdevicemanagementvirtualendpointcloudpcuseraccounttype](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.actions/rename-mgdevicemanagementvirtualendpointcloudpcuseraccounttype)
