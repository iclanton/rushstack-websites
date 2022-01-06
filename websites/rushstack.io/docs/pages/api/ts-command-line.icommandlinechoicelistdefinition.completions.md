---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/ts-command-line](./ts-command-line.md) &gt; [ICommandLineChoiceListDefinition](./ts-command-line.icommandlinechoicelistdefinition.md) &gt; [completions](./ts-command-line.icommandlinechoicelistdefinition.completions.md)

## ICommandLineChoiceListDefinition.completions property

An optional callback that provides a list of custom choices for tab completion.

<b>Signature:</b>

```typescript
completions?: () => Promise<string[]>;
```

## Remarks

This option is only used when `ICommandLineParserOptions.enableTabCompletionAction` is enabled.
