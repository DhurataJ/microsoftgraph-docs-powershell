---
external help file: Microsoft.Graph.Identity.Governance-help.xml
Module Name: Microsoft.Graph.Identity.Governance
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/remove-mgidentitygovernanceaccessreviewdefinitioninstancestagedecision
schema: 2.0.0
---

# Remove-MgIdentityGovernanceAccessReviewDefinitionInstanceStageDecision

## SYNOPSIS
Delete navigation property decisions for identityGovernance

## SYNTAX

### Delete1 (Default)
```
Remove-MgIdentityGovernanceAccessReviewDefinitionInstanceStageDecision
 -AccessReviewInstanceDecisionItemId <String> -AccessReviewInstanceId <String>
 -AccessReviewScheduleDefinitionId <String> -AccessReviewStageId <String> [-IfMatch <String>] [-PassThru]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### DeleteViaIdentity1
```
Remove-MgIdentityGovernanceAccessReviewDefinitionInstanceStageDecision
 -InputObject <IIdentityGovernanceIdentity> [-IfMatch <String>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

## DESCRIPTION
Delete navigation property decisions for identityGovernance

## EXAMPLES

### Example 1
```powershell
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -AccessReviewInstanceDecisionItemId
key: id of accessReviewInstanceDecisionItem

```yaml
Type: String
Parameter Sets: Delete1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AccessReviewInstanceId
key: id of accessReviewInstance

```yaml
Type: String
Parameter Sets: Delete1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AccessReviewScheduleDefinitionId
key: id of accessReviewScheduleDefinition

```yaml
Type: String
Parameter Sets: Delete1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -AccessReviewStageId
key: id of accessReviewStage

```yaml
Type: String
Parameter Sets: Delete1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -IfMatch
ETag

```yaml
Type: String
Parameter Sets: (All)
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
Type: IIdentityGovernanceIdentity
Parameter Sets: DeleteViaIdentity1
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
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/remove-mgidentitygovernanceaccessreviewdefinitioninstancestagedecision](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.governance/remove-mgidentitygovernanceaccessreviewdefinitioninstancestagedecision)
