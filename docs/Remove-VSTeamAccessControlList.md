


# Remove-VSTeamAccessControlList

## SYNOPSIS

Remove access control lists under the specfied security namespace.

## SYNTAX

## DESCRIPTION

Remove access control lists under the specfied security namespace.

## EXAMPLES

## PARAMETERS

### -SecurityNamespace

Security namespace identifier.

```yaml
Type: VSTeamSecurityNamespace
Required: True
```

### -SecurityNamespaceId

Security namespace identifier.

```yaml
Type: String
Required: True
```

### -Tokens

One or more comma-separated security tokens

```yaml
Type: String
Required: True
```

### -Recurse

If true and this is a hierarchical namespace, also remove child ACLs of the specified tokens.

```yaml
Type: Switch
Required: True
```

### -Force

Forces the command without confirmation

```yaml
Type: SwitchParameter
```

## INPUTS

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS
