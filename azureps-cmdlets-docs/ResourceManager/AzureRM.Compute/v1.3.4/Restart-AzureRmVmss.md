---
external help file: Microsoft.Azure.Commands.Compute.dll-Help.xml
online version: .\Get-AzureRmVmss.md
schema: 2.0.0
ms.assetid: 45863A1C-84CF-44F7-899B-9A273B6F661B
---

# Restart-AzureRmVmss

## SYNOPSIS
Restarts the VMSS or a virtual machine within the VMSS.

## SYNTAX

```
Restart-AzureRmVmss [-InformationAction <ActionPreference>] [-InformationVariable <String>]
 [-ResourceGroupName] <String> [-VMScaleSetName] <String> [[-InstanceId] <String[]>] [<CommonParameters>]
```

## DESCRIPTION
The **Restart-AzureRmVmss** cmdlet restarts the Virtual Machine Scale Set (VMSS).
This cmdlet can also be used to restart a specific virtual machine inside the VMSS by using the *InstanceId* parameter.

## EXAMPLES

### Example 1: Restart the VMSS
```
PS C:\>Restart-AzureRmVmss -ResourceGroupName "Group001" -VMScaleSetName "VMSS001";
```

This command restarts the VMSS named VMSS001 that belongs to the resource group named Group001.

### Example 2: Restart a specific virtual machine within the VMSS
```
PS C:\>Restart-AzureRmVmss -ResourceGroupName "Group004" -VMScaleSetName "VMSS001" -InstanceId "1"
```

This command restarts a virtual machine that has the instance ID of 1 in the VMSS named VMSS001 that belongs to the resource group named Group001.

## PARAMETERS

### -InformationAction
@{Text=}```yaml
Type: ActionPreference
Parameter Sets: (All)
Aliases: infa

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InformationVariable
@{Text=}```yaml
Type: String
Parameter Sets: (All)
Aliases: iv

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ResourceGroupName
Specifies the name of the resource group of the VMSS.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -VMScaleSetName
Species the name of the VMSS that this cmdlet restarts.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -InstanceId
Specifies, as a string array, the ID of the instances that need restarted.

```yaml
Type: String[]
Parameter Sets: (All)
Aliases: 

Required: False
Position: 3
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

###  
This cmdlet does not generate any output.

## NOTES

## RELATED LINKS

[Get-AzureRmVmss](.\Get-AzureRmVmss.md)

[New-AzureRmVmss](.\New-AzureRmVmss.md)

[Remove-AzureRmVmss](.\Remove-AzureRmVmss.md)

[Set-AzureRmVmss](.\Set-AzureRmVmss.md)

[Start-AzureRmVmss](.\Start-AzureRmVmss.md)

[Stop-AzureRmVmss](.\Stop-AzureRmVmss.md)

[Update-AzureRmVmss](.\Update-AzureRmVmss.md)

