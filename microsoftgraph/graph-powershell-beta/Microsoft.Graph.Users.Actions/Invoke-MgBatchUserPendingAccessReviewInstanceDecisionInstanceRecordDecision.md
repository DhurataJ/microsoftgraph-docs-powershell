---
external help file: Microsoft.Graph.Users.Actions-help.xml
Module Name: Microsoft.Graph.Users.Actions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.actions/invoke-mgbatchuserpendingaccessreviewinstancedecisioninstancerecorddecision
schema: 2.0.0
---

# Invoke-MgBatchUserPendingAccessReviewInstanceDecisionInstanceRecordDecision

## SYNOPSIS
Invoke action batchRecordDecisions

## SYNTAX

### BatchExpanded (Default)
```
Invoke-MgBatchUserPendingAccessReviewInstanceDecisionInstanceRecordDecision
 -AccessReviewInstanceDecisionItemId <String> -AccessReviewInstanceId <String> -UserId <String>
 [-AdditionalProperties <Hashtable>] [-Decision <String>] [-Justification <String>] [-PrincipalId <String>]
 [-ResourceId <String>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Batch
```
Invoke-MgBatchUserPendingAccessReviewInstanceDecisionInstanceRecordDecision
 -AccessReviewInstanceDecisionItemId <String> -AccessReviewInstanceId <String> -UserId <String>
 -BodyParameter <IPathsSx9PjkUsersUserIdPendingaccessreviewinstancesAccessreviewinstanceIdDecisionsAccessreviewinstancedecisionitemIdInstanceMicrosoftGraphBatchrecorddecisionsPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### BatchViaIdentityExpanded
```
Invoke-MgBatchUserPendingAccessReviewInstanceDecisionInstanceRecordDecision
 -InputObject <IUsersActionsIdentity> [-AdditionalProperties <Hashtable>] [-Decision <String>]
 [-Justification <String>] [-PrincipalId <String>] [-ResourceId <String>] [-PassThru] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### BatchViaIdentity
```
Invoke-MgBatchUserPendingAccessReviewInstanceDecisionInstanceRecordDecision
 -InputObject <IUsersActionsIdentity>
 -BodyParameter <IPathsSx9PjkUsersUserIdPendingaccessreviewinstancesAccessreviewinstanceIdDecisionsAccessreviewinstancedecisionitemIdInstanceMicrosoftGraphBatchrecorddecisionsPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action batchRecordDecisions

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
Parameter Sets: BatchExpanded, Batch
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
Parameter Sets: BatchExpanded, Batch
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
Parameter Sets: BatchExpanded, BatchViaIdentityExpanded
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
Type: IPathsSx9PjkUsersUserIdPendingaccessreviewinstancesAccessreviewinstanceIdDecisionsAccessreviewinstancedecisionitemIdInstanceMicrosoftGraphBatchrecorddecisionsPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Batch, BatchViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Decision
.

```yaml
Type: String
Parameter Sets: BatchExpanded, BatchViaIdentityExpanded
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
Type: IUsersActionsIdentity
Parameter Sets: BatchViaIdentityExpanded, BatchViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Justification
.

```yaml
Type: String
Parameter Sets: BatchExpanded, BatchViaIdentityExpanded
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

### -PrincipalId
.

```yaml
Type: String
Parameter Sets: BatchExpanded, BatchViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceId
.

```yaml
Type: String
Parameter Sets: BatchExpanded, BatchViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UserId
key: id of user

```yaml
Type: String
Parameter Sets: BatchExpanded, Batch
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

### Microsoft.Graph.PowerShell.Models.IPathsSx9PjkUsersUserIdPendingaccessreviewinstancesAccessreviewinstanceIdDecisionsAccessreviewinstancedecisionitemIdInstanceMicrosoftGraphBatchrecorddecisionsPostRequestbodyContentApplicationJsonSchema
### Microsoft.Graph.PowerShell.Models.IUsersActionsIdentity
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.actions/invoke-mgbatchuserpendingaccessreviewinstancedecisioninstancerecorddecision](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.users.actions/invoke-mgbatchuserpendingaccessreviewinstancedecisioninstancerecorddecision)
