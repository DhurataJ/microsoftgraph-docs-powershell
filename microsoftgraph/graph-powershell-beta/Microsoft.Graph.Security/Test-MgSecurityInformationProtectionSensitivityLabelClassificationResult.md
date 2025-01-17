---
external help file: Microsoft.Graph.Security-help.xml
Module Name: Microsoft.Graph.Security
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.security/test-mgsecurityinformationprotectionsensitivitylabelclassificationresult
schema: 2.0.0
---

# Test-MgSecurityInformationProtectionSensitivityLabelClassificationResult

## SYNOPSIS
Invoke action evaluateClassificationResults

## SYNTAX

### EvaluateExpanded (Default)
```
Test-MgSecurityInformationProtectionSensitivityLabelClassificationResult [-AdditionalProperties <Hashtable>]
 [-ClassificationResults <IMicrosoftGraphSecurityClassificationResult[]>]
 [-ContentInfo <IMicrosoftGraphSecurityContentInfo>] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Evaluate
```
Test-MgSecurityInformationProtectionSensitivityLabelClassificationResult
 -BodyParameter <IPaths1P6SiigSecurityInformationprotectionSensitivitylabelsMicrosoftGraphSecurityEvaluateclassificationresultsPostRequestbodyContentApplicationJsonSchema>
 [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action evaluateClassificationResults

## EXAMPLES

## PARAMETERS

### -AdditionalProperties
Additional Parameters

```yaml
Type: Hashtable
Parameter Sets: EvaluateExpanded
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
Type: IPaths1P6SiigSecurityInformationprotectionSensitivitylabelsMicrosoftGraphSecurityEvaluateclassificationresultsPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Evaluate
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -ClassificationResults
.
To construct, please use Get-Help -Online and see NOTES section for CLASSIFICATIONRESULTS properties and create a hash table.

```yaml
Type: IMicrosoftGraphSecurityClassificationResult[]
Parameter Sets: EvaluateExpanded
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ContentInfo
contentInfo
To construct, please use Get-Help -Online and see NOTES section for CONTENTINFO properties and create a hash table.

```yaml
Type: IMicrosoftGraphSecurityContentInfo
Parameter Sets: EvaluateExpanded
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

### Microsoft.Graph.PowerShell.Models.IPaths1P6SiigSecurityInformationprotectionSensitivitylabelsMicrosoftGraphSecurityEvaluateclassificationresultsPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### Microsoft.Graph.PowerShell.Models.IMicrosoftGraphSecurityInformationProtectionAction
## NOTES

ALIASES

COMPLEX PARAMETER PROPERTIES

To create the parameters described below, construct a hash table containing the appropriate properties. For information on hash tables, run Get-Help about_Hash_Tables.


BODYPARAMETER `<IPaths1P6SiigSecurityInformationprotectionSensitivitylabelsMicrosoftGraphSecurityEvaluateclassificationresultsPostRequestbodyContentApplicationJsonSchema>`: .
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ClassificationResults <IMicrosoftGraphSecurityClassificationResult[]>]`: 
    - `[ConfidenceLevel <Int32?>]`: 
    - `[Count <Int32?>]`: 
    - `[SensitiveTypeId <String>]`: 
  - `[ContentInfo <IMicrosoftGraphSecurityContentInfo>]`: contentInfo
    - `[(Any) <Object>]`: This indicates any property can be added to this object.
    - `[ContentFormat <String>]`: 
    - `[Identifier <String>]`: 
    - `[Metadata <IMicrosoftGraphSecurityKeyValuePair[]>]`: 
      - `[Name <String>]`: 
      - `[Value <String>]`: 
    - `[State <String>]`: contentState

CLASSIFICATIONRESULTS <IMicrosoftGraphSecurityClassificationResult\[]>: .
  - `[ConfidenceLevel <Int32?>]`: 
  - `[Count <Int32?>]`: 
  - `[SensitiveTypeId <String>]`: 

CONTENTINFO `<IMicrosoftGraphSecurityContentInfo>`: contentInfo
  - `[(Any) <Object>]`: This indicates any property can be added to this object.
  - `[ContentFormat <String>]`: 
  - `[Identifier <String>]`: 
  - `[Metadata <IMicrosoftGraphSecurityKeyValuePair[]>]`: 
    - `[Name <String>]`: 
    - `[Value <String>]`: 
  - `[State <String>]`: contentState

## RELATED LINKS
