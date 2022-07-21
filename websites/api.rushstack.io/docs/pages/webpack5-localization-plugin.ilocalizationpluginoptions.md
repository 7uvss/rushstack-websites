---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/webpack5-localization-plugin](./webpack5-localization-plugin.md) &gt; [ILocalizationPluginOptions](./webpack5-localization-plugin.ilocalizationpluginoptions.md)

## ILocalizationPluginOptions interface

The options for localization.

**Signature:**

```typescript
export interface ILocalizationPluginOptions
```

## Properties

| Property                                                                                                         | Modifiers | Type                                                                                     | Description                                                                                                                                                                                                                             |
| ---------------------------------------------------------------------------------------------------------------- | --------- | ---------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [globsToIgnore?](./webpack5-localization-plugin.ilocalizationpluginoptions.globstoignore.md)                     |           | string\[\]                                                                               | <i>(Optional)</i> This option is used to specify <code>.resx</code>, <code>.resx.json</code>, and <code>.loc.json</code> files that should not be processed by this plugin.                                                             |
| [localizationStats?](./webpack5-localization-plugin.ilocalizationpluginoptions.localizationstats.md)             |           | [ILocalizationStatsOptions](./webpack5-localization-plugin.ilocalizationstatsoptions.md) | <i>(Optional)</i> Options for how localization stats data should be produced.                                                                                                                                                           |
| [localizedData](./webpack5-localization-plugin.ilocalizationpluginoptions.localizeddata.md)                      |           | [ILocalizedData](./webpack5-localization-plugin.ilocalizeddata.md)                       | Localization data.                                                                                                                                                                                                                      |
| [noStringsLocaleName?](./webpack5-localization-plugin.ilocalizationpluginoptions.nostringslocalename.md)         |           | string                                                                                   | <i>(Optional)</i> The value to replace the \[locale\] token with for chunks without localized strings. Defaults to "none"                                                                                                               |
| [runtimeLocaleExpression?](./webpack5-localization-plugin.ilocalizationpluginoptions.runtimelocaleexpression.md) |           | string                                                                                   | <i>(Optional)</i> A chunk of javascript to use to get the current locale at runtime. If specified, allows the runtime chunk to be non-localized even if it has async localized chunks, as long as it does not directly contain strings. |