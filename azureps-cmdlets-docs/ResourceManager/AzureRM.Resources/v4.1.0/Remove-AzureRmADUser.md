---
external help file: Microsoft.Azure.Commands.Resources.dll-Help.xml
ms.assetid: 9F9B2691-BB3F-4644-BD95-6D74777D1E99
online version:
schema: 2.0.0
content_git_url: https://github.com/Azure/azure-powershell/blob/preview/src/ResourceManager/Resources/Commands.Resources/help/Remove-AzureRmADUser.md
original_content_git_url: https://github.com/Azure/azure-powershell/blob/preview/src/ResourceManager/Resources/Commands.Resources/help/Remove-AzureRmADUser.md
gitcommit: https://github.com/Azure/azure-powershell/blob/928b010f993c0b8148a305b24dcd72d1b9141705
---

# Remove-AzureRmADUser

## SYNOPSIS
Deletes an active directory user.

## SYNTAX

```
Remove-AzureRmADUser -UPNOrObjectId <String> [-Force] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
Deletes an active directory user (work/school account also popularly known as org-id).

## EXAMPLES

### Example 1
```
PS C:\> {{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -Force
If specified, doesn't ask for confirmation for deleting user.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -UPNOrObjectId
The user principal name or the objectId of the user to be deleted.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
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
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[New-AzureRmADUser](./New-AzureRmADUser.md)

[Get-AzureRmADUser](./Get-AzureRmADUser.md)

[Set-AzureRmADUser](./Set-AzureRmADUser.md)

