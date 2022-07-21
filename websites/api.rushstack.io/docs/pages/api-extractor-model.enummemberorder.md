---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@microsoft/api-extractor-model](./api-extractor-model.md) &gt; [EnumMemberOrder](./api-extractor-model.enummemberorder.md)

## EnumMemberOrder enum

Options for customizing the sort order of [ApiEnum](./api-extractor-model.apienum.md) members.

**Signature:**

```typescript
export declare enum EnumMemberOrder
```

## Enumeration Members

| Member   | Value                             | Description                                                                                                                                                                                                                                                                                           |
| -------- | --------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ByName   | <code>&quot;by-name&quot;</code>  | <p><code>ApiEnumMember</code> items are sorted according to their [ApiItem.getSortKey()](./api-extractor-model.apiitem.getsortkey.md) . The order is basically alphabetical by identifier name, but otherwise unspecified to allow for cosmetic improvements.</p><p>This is the default behavior.</p> |
| Preserve | <code>&quot;preserve&quot;</code> | <code>ApiEnumMember</code> items preserve the original order of the declarations in the source file. (This disables the automatic sorting that is normally applied based on [ApiItem.getSortKey()](./api-extractor-model.apiitem.getsortkey.md) .)                                                    |