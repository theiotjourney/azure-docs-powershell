---
external help file: Microsoft.AzureStack.AzureConsistentStorage.Commands.dll-Help.xml
online version: 
schema: 2.0.0
---

# Get-AzsStorageFarm

## SYNOPSIS
Gets the Storage properties and settings for a specified region or farm.

## SYNTAX

```
Get-AzsStorageFarm [-Name <String>] [-SkipCertificateValidation]
```

## DESCRIPTION
The **Get-AzsStorageFarm** cmdlet gets the Storage properties and settings for a specified region or farm.

## PARAMETERS

### -Name
Specifies the name of the Azs farm that this cmdlet gets.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -SkipCertificateValidation
Indicates that the cmdlet does not validate the certificate.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see about_CommonParameters (http://go.microsoft.com/fwlink/?LinkID=113216).

## RELATED LINKS

[Set-AzsStorageFarm](./Set-AzsStorageFarm.md)


