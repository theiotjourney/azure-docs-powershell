---
external help file: Microsoft.Azure.Commands.Automation.dll-Help.xml
online version: 
schema: 2.0.0
ms.assetid: CEF4C4BC-FBE3-4636-8098-28B313CD8E62
---

# New-AzureAutomationModule

## SYNOPSIS
Imports a module into Azure Automation.

## SYNTAX

```
New-AzureAutomationModule [-Name] <String> [-ContentLink] <Uri> [-Tags <IDictionary>]
 [-AutomationAccountName] <String> [-Profile <AzureProfile>] [<CommonParameters>]
```

## DESCRIPTION
The **New-AzureAutomationModule** cmdlet imports a module into Azure Automation.
A module is a compressed file, with a .zip extension, that contains a folder which includes one of the following file types:

- A Windows PowerShell module (psm1 file). 

- A Windows PowerShell module manifest (psd1 file). 

- An assembly (dll file)

The names of the zip file, the folder in the zip file, and file in the folder (.psm1, psd.1, or .dll) must match.

## EXAMPLES

### Example 1: Import a module
```
PS C:\> New-AzureAutomationModule -AutomationAccountName "Contoso17" -Name "ContosoModule" -ContentLink "http://contosostorage.blob.core.windows.net/modules/ContosoModule.zip"
```

This command imports a module named ContosoModule into the Azure Automation account named Contoso17.
The module is stored in an Azure blob in a storage account called contosostorage and a container called modules.

## PARAMETERS

### -AutomationAccountName
Specifies the name of the automation account the module will be stored in.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -ContentLink
Public URL such as a website or Azure blob storage specifying the path to the module file. 
This location must be publically accessible.

```yaml
Type: Uri
Parameter Sets: (All)
Aliases: 

Required: True
Position: 3
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Tags
Specifies one or more tags related to the module.

```yaml
Type: IDictionary
Parameter Sets: (All)
Aliases: Tag

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Profile
In-memory profile.

```yaml
Type: AzureProfile
Parameter Sets: (All)
Aliases: 

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

###  
Microsoft.Azure.Commands.Automation.Model.Module

## NOTES

## RELATED LINKS

[Get-AzureAutomationModule](./Get-AzureAutomationModule.md)

[Set-AzureAutomationModule](./Set-AzureAutomationModule.md)

[Remove-AzureAutomationModule](./Remove-AzureAutomationModule.md)


