---
title: NavigationHistoryEntry.sameDocument
slug: Web/API/NavigationHistoryEntry/sameDocument
page-type: web-api-instance-property
tags:
  - API
  - Experimental
  - History
  - Navigate
  - Navigation
  - Navigation API
  - Property
  - Read-only
  - Reference
  - sameDocument
  - Scroll
  - Traversal
browser-compat: api.NavigationHistoryEntry.sameDocument
---

{{APIRef("Navigation API")}}{{seecompattable}}

The **`sameDocument`** read-only property of the
{{domxref("NavigationHistoryEntry")}} interface returns `true` if this history entry is for the same `document` as the current {{domxref("Document")}} value, or `false` otherwise.

## Value

A boolean.

## Examples

```js
const current = navigation.currentEntry;
console.log(current.sameDocument);
// Will always return true
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- [Modern client-side routing: the Navigation API](https://developer.chrome.com/docs/web-platform/navigation-api/)
- [Navigation API explainer](https://github.com/WICG/navigation-api/blob/main/README.md)
- Domenic Denicola's [Navigation API live demo](https://gigantic-honored-octagon.glitch.me/)
