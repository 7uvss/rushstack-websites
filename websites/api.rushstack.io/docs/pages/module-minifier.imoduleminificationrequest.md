---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/module-minifier](./module-minifier.md) &gt; [IModuleMinificationRequest](./module-minifier.imoduleminificationrequest.md)

## IModuleMinificationRequest interface

Request to the minifier

**Signature:**

```typescript
export interface IModuleMinificationRequest 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [code](./module-minifier.imoduleminificationrequest.code.md) |  | string | The raw code fragment |
|  [externals](./module-minifier.imoduleminificationrequest.externals.md) |  | string\[\] \| undefined | Reserved variable names, e.g. \_\_WEBPACK\_EXTERNAL\_MODULE\_1\_\_ |
|  [hash](./module-minifier.imoduleminificationrequest.hash.md) |  | string | Identity of the request. Will be included in the response. |
|  [nameForMap](./module-minifier.imoduleminificationrequest.nameformap.md) |  | string \| undefined | File name to show for the source code in the source map |
