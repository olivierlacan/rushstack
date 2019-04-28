<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/ts-command-line](./ts-command-line.md) &gt; [CommandLineParameterProvider](./ts-command-line.commandlineparameterprovider.md) &gt; [defineFlagParameter](./ts-command-line.commandlineparameterprovider.defineflagparameter.md)

## CommandLineParameterProvider.defineFlagParameter() method

Defines a command-line switch whose boolean value is true if the switch is provided, and false otherwise.

<b>Signature:</b>

```typescript
defineFlagParameter(definition: ICommandLineFlagDefinition): CommandLineFlagParameter;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  definition | <code>ICommandLineFlagDefinition</code> |  |

<b>Returns:</b>

`CommandLineFlagParameter`

## Remarks

Example: example-tool --debug
