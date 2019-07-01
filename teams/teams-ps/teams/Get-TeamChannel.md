---
external help file: Microsoft.TeamsCmdlets.PowerShell.Custom.dll-Help.xml
Module Name: MicrosoftTeams
online version:
schema: 2.0.0
author: kenwith
ms.author: kenwith
ms.reviewer:
---

# Get-TeamChannel

## SYNOPSIS

Get all the channels for a team.

## SYNTAX

```
Get-TeamChannel -GroupId <String> [-MembershipType <String>] [<CommonParameters>]
```

## DESCRIPTION
This cmdlet supports retrieving the channels with particular properties/information that a specific user belongs to in a specific team.

## EXAMPLES

### Example 1
```
Get-TeamChannel -GroupId af55e84c-dc67-4e48-9005-86e0b07272f9
```

```
Get-TeamChannel -GroupId af55e84c-dc67-4e48-9005-86e0b07272f9 -MembershipType "Standard"
```

## PARAMETERS

### -GroupId
GroupId of the team

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

### -MembershipType (available only in private preview)
Membership type of the channel in the team

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

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable.
For more information, see about_CommonParameters (https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS
