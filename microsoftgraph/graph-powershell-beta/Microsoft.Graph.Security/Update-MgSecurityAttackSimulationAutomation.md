---
external help file: Microsoft.Graph.Security-help.xml
Module Name: Microsoft.Graph.Security
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.security/update-mgsecurityattacksimulationautomation
schema: 2.0.0
---

# Update-MgSecurityAttackSimulationAutomation

## SYNOPSIS
Represents simulation automations created to run on a tenant.

## SYNTAX

### UpdateExpanded (Default)
```
Update-MgSecurityAttackSimulationAutomation -SimulationAutomationId <String>
 [-AdditionalProperties <Hashtable>] [-CreatedBy <IMicrosoftGraphEmailIdentity>] [-CreatedDateTime <DateTime>]
 [-Description <String>] [-DisplayName <String>] [-Id <String>]
 [-LastModifiedBy <IMicrosoftGraphEmailIdentity>] [-LastModifiedDateTime <DateTime>]
 [-LastRunDateTime <DateTime>] [-NextRunDateTime <DateTime>] [-Runs <IMicrosoftGraphSimulationAutomationRun[]>]
 [-Status <String>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Update
```
Update-MgSecurityAttackSimulationAutomation -SimulationAutomationId <String>
 -BodyParameter <IMicrosoftGraphSimulationAutomation> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentityExpanded
```
Update-MgSecurityAttackSimulationAutomation -InputObject <ISecurityIdentity>
 [-AdditionalProperties <Hashtable>] [-CreatedBy <IMicrosoftGraphEmailIdentity>] [-CreatedDateTime <DateTime>]
 [-Description <String>] [-DisplayName <String>] [-Id <String>]
 [-LastModifiedBy <IMicrosoftGraphEmailIdentity>] [-LastModifiedDateTime <DateTime>]
 [-LastRunDateTime <DateTime>] [-NextRunDateTime <DateTime>] [-Runs <IMicrosoftGraphSimulationAutomationRun[]>]
 [-Status <String>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### UpdateViaIdentity
```
Update-MgSecurityAttackSimulationAutomation -InputObject <ISecurityIdentity>
 -BodyParameter <IMicrosoftGraphSimulationAutomation> [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Represents simulation automations created to run on a tenant.

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
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -BodyParameter
simulationAutomation
To construct, please use Get-Help -Online and see NOTES section for BODYPARAMETER properties and create a hash table.

```yaml
Type: IMicrosoftGraphSimulationAutomation
Parameter Sets: Update, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -CreatedBy
emailIdentity
To construct, please use Get-Help -Online and see NOTES section for CREATEDBY properties and create a hash table.

```yaml
Type: IMicrosoftGraphEmailIdentity
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -CreatedDateTime
Date and time when the attack simulation automation was created.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Description
Description of the attack simulation automation.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DisplayName
Display name of the attack simulation automation.
Supports $filter and $orderby.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Id
Read-only.

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

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
Type: ISecurityIdentity
Parameter Sets: UpdateViaIdentityExpanded, UpdateViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -LastModifiedBy
emailIdentity
To construct, please use Get-Help -Online and see NOTES section for LASTMODIFIEDBY properties and create a hash table.

```yaml
Type: IMicrosoftGraphEmailIdentity
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastModifiedDateTime
Date and time when the attack simulation automation was most recently modified.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -LastRunDateTime
Date and time of the latest run of the attack simulation automation.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -NextRunDateTime
Date and time of the upcoming run of the attack simulation automation.

```yaml
Type: DateTime
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
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

### -Runs
A collection of simulation automation runs.
To construct, please use Get-Help -Online and see NOTES section for RUNS properties and create a hash table.

```yaml
Type: IMicrosoftGraphSimulationAutomationRun[]
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SimulationAutomationId
key: id of simulationAutomation

```yaml
Type: String
Parameter Sets: UpdateExpanded, Update
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Status
simulationAutomationStatus

```yaml
Type: String
Parameter Sets: UpdateExpanded, UpdateViaIdentityExpanded
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

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSimulationAutomation
### Microsoft.Graph.PowerShell.Models.ISecurityIdentity
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.security/update-mgsecurityattacksimulationautomation](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.security/update-mgsecurityattacksimulationautomation)
