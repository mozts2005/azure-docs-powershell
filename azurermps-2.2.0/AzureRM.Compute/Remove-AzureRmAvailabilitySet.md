---
external help file: Microsoft.Azure.Commands.Compute.dll-Help.xml
ms.assetid: E1E49576-BFC0-4D07-B25B-67947D7D66FE
online version:
schema: 2.0.0
---

# Remove-AzureRmAvailabilitySet

## SYNOPSIS
Removes an availability set from Azure.

## SYNTAX

```
Remove-AzureRmAvailabilitySet [-ResourceGroupName] <String> [[-Name] <String>] [-Force]
 [-InformationAction <ActionPreference>] [-InformationVariable <String>] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-AzureRmAvailabilitySet** cmdlet removes an availability set from Azure.

## EXAMPLES

### Example 1: Remove an availability set
```
PS C:\>Remove-AzureRmAvailabilitySet -Name "AvailabilitySet03" -ResourceGroupName "ResourceGroup11"
```

This command removes an availability set named AvailablitySet03 in the resource group named ResourceGroup11.

## PARAMETERS

### -ResourceGroupName
Specifies the name of a resource group.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Name
Specifies the name of the availability set to remove.

```yaml
Type: String
Parameter Sets: (All)
Aliases: ResourceName, AvailabilitySetName

Required: False
Position: 1
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -Force
Forces the command to run without asking for user confirmation.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases:

Required: False
Position: 2
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

[Get-AzureRmAvailabilitySet](./Get-AzureRmAvailabilitySet.md)

[New-AzureRmAvailabilitySet](./New-AzureRmAvailabilitySet.md)
