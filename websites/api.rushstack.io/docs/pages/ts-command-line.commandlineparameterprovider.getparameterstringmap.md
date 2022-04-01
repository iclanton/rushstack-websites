---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/ts-command-line](./ts-command-line.md) &gt; [CommandLineParameterProvider](./ts-command-line.commandlineparameterprovider.md) &gt; [getParameterStringMap](./ts-command-line.commandlineparameterprovider.getparameterstringmap.md)

## CommandLineParameterProvider.getParameterStringMap() method

Returns a object which maps the long name of each parameter in this.parameters to the stringified form of its value. This is useful for logging telemetry, but it is not the proper way of accessing parameters or their values.

<b>Signature:</b>

```typescript
getParameterStringMap(): Record<string, string>;
```

<b>Returns:</b>

Record&lt;string, string&gt;