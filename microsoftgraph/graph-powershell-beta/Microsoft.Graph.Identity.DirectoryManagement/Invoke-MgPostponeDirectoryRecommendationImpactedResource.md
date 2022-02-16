---
external help file: Microsoft.Graph.Identity.DirectoryManagement-help.xml
Module Name: Microsoft.Graph.Identity.DirectoryManagement
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.directorymanagement/invoke-mgpostponedirectoryrecommendationimpactedresource
schema: 2.0.0
---

# Invoke-MgPostponeDirectoryRecommendationImpactedResource

## SYNOPSIS
Invoke action postpone

## SYNTAX

### PostponeExpanded (Default)
```
Invoke-MgPostponeDirectoryRecommendationImpactedResource -RecommendationId <String>
 -RecommendationResourceId <String> [-AdditionalProperties <Hashtable>] [-PostponeUntilDateTime <DateTime>]
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Postpone
```
Invoke-MgPostponeDirectoryRecommendationImpactedResource -RecommendationId <String>
 -RecommendationResourceId <String>
 -BodyParameter <IPathsU2678MDirectoryRecommendationsRecommendationIdImpactedresourcesRecommendationresourceIdMicrosoftGraphPostponePostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

### PostponeViaIdentityExpanded
```
Invoke-MgPostponeDirectoryRecommendationImpactedResource -InputObject <IIdentityDirectoryManagementIdentity>
 [-AdditionalProperties <Hashtable>] [-PostponeUntilDateTime <DateTime>] [-WhatIf] [-Confirm]
 [<CommonParameters>]
```

### PostponeViaIdentity
```
Invoke-MgPostponeDirectoryRecommendationImpactedResource -InputObject <IIdentityDirectoryManagementIdentity>
 -BodyParameter <IPathsU2678MDirectoryRecommendationsRecommendationIdImpactedresourcesRecommendationresourceIdMicrosoftGraphPostponePostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action postpone

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
Parameter Sets: PostponeExpanded, PostponeViaIdentityExpanded
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
Type: IPathsU2678MDirectoryRecommendationsRecommendationIdImpactedresourcesRecommendationresourceIdMicrosoftGraphPostponePostRequestbodyContentApplicationJsonSchema
Parameter Sets: Postpone, PostponeViaIdentity
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
Type: IIdentityDirectoryManagementIdentity
Parameter Sets: PostponeViaIdentityExpanded, PostponeViaIdentity
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -PostponeUntilDateTime
.

```yaml
Type: DateTime
Parameter Sets: PostponeExpanded, PostponeViaIdentityExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RecommendationId
key: id of recommendation

```yaml
Type: String
Parameter Sets: PostponeExpanded, Postpone
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RecommendationResourceId
key: id of recommendationResource

```yaml
Type: String
Parameter Sets: PostponeExpanded, Postpone
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

### Microsoft.Graph.PowerShell.Models.IIdentityDirectoryManagementIdentity
### Microsoft.Graph.PowerShell.Models.IPathsU2678MDirectoryRecommendationsRecommendationIdImpactedresourcesRecommendationresourceIdMicrosoftGraphPostponePostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphRecommendationResource
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.directorymanagement/invoke-mgpostponedirectoryrecommendationimpactedresource](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.identity.directorymanagement/invoke-mgpostponedirectoryrecommendationimpactedresource)
