---
Author: Paul Boyer
external help file: PSVault-Utilities-help.xml
Module Guid: 8ce86084-d7bb-482e-9729-9d3048ff0c61
Module Name: PSVault-Utilities
online version:
schema: 2.0.0
---

# Apply-CodeSignature

## SYNOPSIS
Script to automate signing of other scripts with digital certificate

## SYNTAX

```
Apply-CodeSignature [-FilePath] <String> [<CommonParameters>]
```

## DESCRIPTION
Automatically grab a code signing certificate from the current user certificate store (after checking that a code signing certificate exists). 
Then append that certificate to the end of the code file.

## EXAMPLES

### EXAMPLE 1
```
Apply-CodeSignature -FilePath "path to file"
```

### EXAMPLE 2
```
Apply-CodeSignature "path to file"
```

## PARAMETERS

### -FilePath
FilePath to the file that will be digitally signed with the code signing certificate.
Note that the parameter is positionally bound and does not need to be called explicitly.

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_signing?view=powershell-7.1](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_signing?view=powershell-7.1)

