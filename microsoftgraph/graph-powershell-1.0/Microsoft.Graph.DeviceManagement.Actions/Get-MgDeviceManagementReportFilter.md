---
external help file: Microsoft.Graph.DeviceManagement.Actions-help.xml
Module Name: Microsoft.Graph.DeviceManagement.Actions
online version: https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.actions/get-mgdevicemanagementreportfilter
schema: 2.0.0
---

# Get-MgDeviceManagementReportFilter

## SYNOPSIS
Invoke action getReportFilters

## SYNTAX

### GetExpanded1 (Default)
```
Get-MgDeviceManagementReportFilter -OutFile <String> [-AdditionalProperties <Hashtable>] [-Filter <String>]
 [-GroupBy <String[]>] [-Name <String>] [-Property <String[]>] [-Search <String>] [-SessionId <String>]
 [-Skip <Int32>] [-Sort <String[]>] [-Top <Int32>] [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

### Get1
```
Get-MgDeviceManagementReportFilter -OutFile <String>
 -BodyParameter <IPaths1J4Do9UDevicemanagementReportsMicrosoftGraphGetreportfiltersPostRequestbodyContentApplicationJsonSchema>
 [-PassThru] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Invoke action getReportFilters

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
Parameter Sets: GetExpanded1
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
Type: IPaths1J4Do9UDevicemanagementReportsMicrosoftGraphGetreportfiltersPostRequestbodyContentApplicationJsonSchema
Parameter Sets: Get1
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByValue)
Accept wildcard characters: False
```

### -Filter
.

```yaml
Type: String
Parameter Sets: GetExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -GroupBy
.

```yaml
Type: String[]
Parameter Sets: GetExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
.

```yaml
Type: String
Parameter Sets: GetExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OutFile
Path to write output file to

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
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

### -Property
.

```yaml
Type: String[]
Parameter Sets: GetExpanded1
Aliases: Select

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Search
.

```yaml
Type: String
Parameter Sets: GetExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SessionId
.

```yaml
Type: String
Parameter Sets: GetExpanded1
Aliases:

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Sort
.

```yaml
Type: String[]
Parameter Sets: GetExpanded1
Aliases: OrderBy

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Top
.

```yaml
Type: Int32
Parameter Sets: GetExpanded1
Aliases: Limit

Required: False
Position: Named
Default value: 0
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

### -Skip
.

```yaml
Type: Int32
Parameter Sets: GetExpanded1
Aliases:

Required: False
Position: Named
Default value: 0
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### Microsoft.Graph.PowerShell.Models.IPaths1J4Do9UDevicemanagementReportsMicrosoftGraphGetreportfiltersPostRequestbodyContentApplicationJsonSchema
## OUTPUTS

### System.Boolean
## NOTES
Please use Get-Help -Online.

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.actions/get-mgdevicemanagementreportfilter](https://docs.microsoft.com/en-us/powershell/module/microsoft.graph.devicemanagement.actions/get-mgdevicemanagementreportfilter)
