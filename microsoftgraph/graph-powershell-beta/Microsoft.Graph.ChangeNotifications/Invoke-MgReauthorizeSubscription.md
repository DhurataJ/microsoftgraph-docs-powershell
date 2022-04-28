---
external help file: Microsoft.Graph.ChangeNotifications-help.xml
Module Name: Microsoft.Graph.ChangeNotifications
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.changenotifications/invoke-mgreauthorizesubscription
schema: 2.0.0
---

# Invoke-MgReauthorizeSubscription

## SYNOPSIS
Invoke action reauthorize

## SYNTAX

### Reauthorize1 (Default)
```
Invoke-MgReauthorizeSubscription -SubscriptionId <String> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### ReauthorizeViaIdentity1
```
Invoke-MgReauthorizeSubscription -InputObject <IChangeNotificationsIdentity> [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Invoke action reauthorize

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -InputObject
Identity Parameter
To construct, please use Get-Help -Online and see NOTES section for INPUTOBJECT properties and create a hash table.

```yaml
Type: IChangeNotificationsIdentity
Parameter Sets: ReauthorizeViaIdentity1
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

### -SubscriptionId
key: id of subscription

```yaml
Type: String
Parameter Sets: Reauthorize1
Aliases:

Required: True
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

### Microsoft.Graph.PowerShell.Models.IChangeNotificationsIdentity
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.changenotifications/invoke-mgreauthorizesubscription](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.changenotifications/invoke-mgreauthorizesubscription)
